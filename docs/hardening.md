# Ubuntu hardening
SSH: parol o’chirilgan (01-hardening.conf), faqat ed25519 kalit
ufw: deny incoming, faqat OpenSSH
Fail2ban: sshd jail, 5 urinish -> 1 soat ban
Tekshiruv: sshd -T, Kali’dan test, journalctl audit
