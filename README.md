python seeker.py & cloudflared tunnel --url http://127.0.0.1:8080
# termux-codes-5
# 📥 لومړی وار په نوي موبایل کې د انسټالولو کمانډونه

### 1️⃣ لومړی ګام (د اړینو اوزارو انسټالول):
```bash
pkg update && pkg install python python-numpy clang cloudflared -y
```

### 2️⃣ دوهم ګام (د Seeker کوډ په اتومات ډول جوړول):
```bash
cat << 'EOF' > seeker.py
import os
import sys

def main():
    print("\n\t[+] Seeker ابزار په بریالیتوب سره خلاص شو! [+]")
    print("\t=========================================")
    print("\t Google Template (ګوګل)")
    print("\t YouTube Template (یوټیوب)")
    print("\t WhatsApp Template (واټساپ)")
    print("\t=========================================")
    try:
        choice = input("\n[?] یو نمبر انتخاب کړه: ")
        print(f"\n[+] ستا انتخاب {choice} تایید شو. د لینک جوړولو لپاره انټرنیټ او فیلټرشکن وګوره.")
    except KeyboardInterrupt:
        print("\n[-] بند شو.")

if __name__ == "__main__":
    main()
EOF
```

---

# 🚀 هر وار د پروګرام د چلولو او لینک جوړولو کمانډ

### 3️⃣ درېیم ګام (د پروګرام خلاصول او د کلاوډفلیر لینک چمتو کول):
```bash
python seeker.py & cloudflared tunnel --url http://127.0.0.1:8080
```
