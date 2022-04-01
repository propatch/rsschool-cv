https://propatch.github.io/rsschool-cv/cv


:::row:::
   :::column span="2":::
      **This is a 2-span column with lots of text.**

      Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec vestibulum mollis nunc
      ornare commodo. Nullam ac metus imperdiet, rutrum justo vel, vulputate leo. Donec
      rutrum non eros eget consectetur.
   :::column-end:::
   :::column span="":::
      **This is a single-span column with an image in it.**

      ![Doc.U.Ment](media/markdown-reference/document.png)
   :::column-end:::
:::row-end:::

:::row:::
    :::column:::
        ### Konstantin Bazhenov
        =========================
        ### Developer - Kotlin / JS
        Graduated from the Faculty of Autonomous Control Systems in 2009. After 5 years of wandering ... fate brought me to the computer. Now with him on "you".
    :::column-end:::
    :::column:::
        :::image type="content" source="img/avatar-user.png" alt-text="Avatar":::
    :::column-end:::
:::row-end:::

#### **Contact information**

|         |         |
|---------|---------|
|e-mail:     | `propatchme@gmail.com`|
|tel:        | `+79604705550`        |
|telegram:   | `propatchru`          |
|instagram   |  [`propatch.it`](https://www.instagram.com/propatch.it)          |
| discord    |  `propatch#0646`      |

#### **Editors**

:::row:::
    :::column:::
        ![VSCode](/img/Visual_Studio_Code_1.35_icon.svg.ico)
        ![IntelliJ IDEA](/img/IntelliJ_IDEA_Icon.svg.ico)
        ![ubuntu OS](img/OS-Ubuntu.ico)
        ![Android SDK](/img/Android-Studio-Logo.ico)
    :::column-end:::
    :::column:::
        `using the Pop_OS/Ubuntu`

        **`VSCode`**
        **`Android SDK`**
        **`IntelliJ IDEA`**
    :::column-end:::
:::row-end:::

### Education
> Epam RSSchool (2022), **"Web-developer"**

> WebHeroSchool(2020), **"Freelance"**

> LoftSchool (2017), **"Web-developer"**

> Rostov Military Institute of Rocket Troops, Control and informatics in technical systems (2004 - 2009), **"Engineer"**

### Skills 
> JavaScript

> Kotlin

> SQL

> Adobe Photoshop

> Git

### Code examples
![My level codewars!](https://www.codewars.com/users/propatch/badges/large "Codewars propatch")
```sql
SELECT name, ifnull((
	SELECT count (id)
	FROM companies1
	 WHERE companies1.city_id in (
		SELECT cities1.id  
			FROM cities1
			 WHERE cities1.id = countries1.id AND companies1.labors >= 1000 
	 )
),0) as COUNTCOMPANIES
FROM countries1
GROUP BY countries1.name;

SELECT countries1.name, count(*) as COUNTCOMPANIES
 FROM countries1
	LEFT JOIN cities1 ON countries1.id = cities1.country_id
	LEFT JOIN companies1 ON cities1.id = companies1.city_id
		WHERE companies1.labors >= 1000
GROUP BY countries1.name;
```

### Experience

**Site with my works** [propatch.ru](http://propatch.ru/)   
> Freelancer ( since 2017 )

> Senior engineers of the Department ofCommunications Computing and Special  Equipment ( since 2013 )

### Languages
`Russian and English (A2)`
