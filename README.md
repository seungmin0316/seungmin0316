def create_github_readme():
    content = """# 안녕하세요! 👋

데이터와 논리적인 프레임워크를 통해 문제를 해결하는 것을 즐기는 학생 개발자입니다. 

---

### 🛠 Tech Stack

**Languages & Tools**
* **Languages:** `Python`, `Java`, `C++`, `SQL`
* **Tools:** `Git`, `VS Code`, `IntelliJ`, `Notion`
* **Fields:** `Data Analysis`, `AI Ethics`, `Algorithms`

---

### 💡 Interests

* **Analytical Frameworks:** '5 Whys'와 같은 기법을 활용해 일상과 프로젝트의 문제를 분석하고 최적화하는 것을 좋아합니다.
* **Animation & Culture:** 독립 애니메이션의 서사와 언어적 표현이 주는 인문학적 영감에 관심이 있습니다.
* **Collaboration:** 협업 환경에서의 효율적인 버전 관리와 커뮤니케이션 도구에 대해 깊이 고민합니다.
* **AI & Ethics:** 인공지능 기술의 발전과 그에 따르는 윤리적 책임에 대해 항상 주목하고 있습니다.

---

### 📈 GitHub Stats

![GitHub stats](https://github-readme-stats.vercel.app/api?username=YOUR_USERNAME&show_icons=true&theme=radical)

---

### 📫 Contact

* **Email:** your-email@example.com
* **Blog/Portfolio:** [링크]
* **LinkedIn:** [링크]
"""
    
    with open("README.md", "w", encoding="utf-8") as f:
        f.write(content)
        print("README.md 파일이 성공적으로 생성되었습니다.")

if __name__ == "__main__":
    create_github_readme()
