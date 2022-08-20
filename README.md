- 👋 Hi, I’m @Yvsharma
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
Yvsharma/Yvsharma is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
if __name__ == '__main__':
    n = int(input().strip())
if n % 2 != 0:
    print ("Weird")
else:
    if n >= 2 and n <= 5:
        print ("Not Weird")
    elif n >= 6 and n <= 20:
        print ("Weird")
    elif n > 20:
        print ("Not Weird")
