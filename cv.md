https://github.com/propatch/rsschool-cv/cv




:::row:::
    :::column:::
        > ### Konstantin Bazhenov
        =========================
        ### Developer - Kotlin / JS
    :::column-end:::
    :::column:::
        :::image type="content" source="img/avatar-user.png" alt-text="Avatar":::
    :::column-end:::
:::row-end:::

#### **Contact information**

| |  |
|---------|---------|
|e-mail:     | `propatchme@gmail.com`|
|tel:        | `+79604705550`        |
|telegram:   | `propatchru`          |
|instagram   |  [`propatch.it`](https://www.instagram.com/propatch.it)          |
| discord    |  `propatch#0646`      |
|

#### **Editors**

:::row:::
    :::column:::
        ![VSCode](/img/Visual_Studio_Code_1.35_icon.svg.ico)
        ![IntelliJ IDEA](/img/IntelliJ_IDEA_Icon.svg.ico)
        ![Android SDK](/img/Android-Studio-Logo.ico)
        ![ubuntu OS](img/OS-Ubuntu.ico)
    :::column-end:::
    :::column:::
        `using the Pop_OS/Ubuntu`

        `VSCode`
        `Android SDK`
        `IntelliJ IDEA`
        

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

[**Site with my works propatch.ru**](http://propatch.ru/)   
> Freelancer ( since 2017 )

> Senior engineers of the Department ofCommunications Computing and Special  Equipment ( since 2013 )

codewars  

### Languages
`Russian and English (A2)`
