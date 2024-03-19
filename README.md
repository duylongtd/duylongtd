
<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=500&size=25&pause=1000&color=55B4B0&width=435&lines=XAO+CH%C3%8CN+XIN+CH%C3%80O+%3E.%3C+" alt="Typing SVG" />
</p>

<div>
  <img src="https://64.media.tumblr.com/971f9f2f8753acb0fd8568b24afd1e0a/24e405a8028c52e5-84/s2048x3072/1b4d0d4e9f67cd8da66dc72e3986d7fd198a03fe.gifv" style="height: 600px; width: 100%; object-fit: contain;">
</div>

## Hi there, I'm Tran Dinh Duy Long 👋

[![Facebook](https://img.shields.io/badge/Facebook-1877F2?style=for-the-badge&logo=facebook&logoColor=white)](https://www.facebook.com/longkvui)
[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:tranlong280403@gmail.com)
[![Instagram](https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://www.instagram.com/lwng284/)
[![View - duylongtd CV](https://img.shields.io/badge/View-duylongtd_CV-2ea44f?style=for-the-badge&logo=https%3A%2F%2Fimages.vexels.com%2Fmedia%2Fusers%2F3%2F140030%2Fisolated%2Fpreview%2F521136d25b37386f49728b93d2e4e6fa-cv-icon.png&logoColor=white)](https://drive.google.com/file/d/1sV9xs0nPdAYXiCagffXFzqboJ8uuyfNo/view)


- I am a 3nd-year student at `FPT University`, and I am a person who loves to learn and tinker with code.
- My strength is `Java` language, I am looking for jobs related to this language. I can work full time or part time jobs.
- I'm a `football enthusiast`, like to listen to `ballad` or `indie music`, but my mind is not too sad (sometimes) hahaha... Just a brief introduction. Thank you for visiting my `GitHub`.
    
  ```Java
    /**
	 *  MY PERSONAL DETAIL
	 */
  
    public enum Gender {
      MALE,
      FEMALE
    }

    @AllArgsConstructor
    @NoArgsConstructor
    @FieldDefaults(level = AccessLevel.PRIVATE)
    @Data
    public class PersonalDetail {
  
      String name;
      long age; //Declare the data type as `long` to expect to live long
      Gender gender;
      String university;
      boolean single;
      int experience;
      byte currentYearInUniversity;
      List<String> hobby;

      public void sayHello(String message) {
          System.out.println(message);
      }
    }

    @SpringBootApplication
    public class Main {
  
      public static void main(String[] args) {
          int age = 21;
          int experienceYear = 1;
          byte studyYear = 3;
          boolean isSingle = true;
          List<String> listHobbies = new ArrayList (
              Arrays.asList("Football", "Music", "Cooking")
          );
  
          PersonalDetail duylongtd = new PersonalDetail (
              "Trần Đình Duy Long",
              age,
              Gender.MALE,
              "FPT University",
              isSingle,
              experienceYear,
              studyYear,
              listHobbies
          );

          String message = "Thank you for visiting my GitHub page";
          duylongtd.sayHello(message);
          SpringApplication.run(Main.class, args);
      }
    }
  ```

## 🐼 GitHub Stats 🐈
<p align="center">
  <img height="180em" src="https://github-readme-stats.vercel.app/api?username=duylongtd&show_icons=true&hide_border=true&&count_private=true&include_all_commits=true&theme=tokyonight" />
  <img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=duylongtd&theme=dark&show_icons=true&hide_border=true&layout=compact&langs_count=8" />
</p>

![](https://komarev.com/ghpvc/?username=duylongtd&label=VISITOR+VIEW&color=ff69b4)

