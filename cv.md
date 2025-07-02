# [rsschool-cv](https://DaurenZh.github.io/rsschool-cv/cv)

# Dauren Zhylkybayev
## __Contacts__ 

* Email: zhylkybaevdauren@gmail.com
* Phone: +7-(700)-216-38-36
* Github: DaurenZh
* Telegram: @drnwght
* LinkedIn: https://www.linkedin.com/in/dauren-zhylkybayev-3b55a1310/
* Discord: dngnmstr

***
***Goal***: Aim to develop my skills in WebDev and LLM areas.

__Strengths__: Can work with tight deadlines, under pressure. 
Love to work on small features. Try to be active and offer my ideas to the team. Interested in improving my soft and hard skills. 

__Experience__: Worked as Jun Dev in outsourcing area. Faced interesting tasks, fixed bugs. 

***
## __Skills__

* HTML/CSS (Fundementals)
* JavaScript (Fundementals)
* Git 
* SQL 
***

### Code Example

``` 
const { handleExpress } = require("../utils/handle-express");
const router = require("express").Router();
const { authMiddleware } = require("./middlewares/auth");

router.use(authMiddleware);

// Get categories
router.get("/", (req, res) => {
  handleExpress(res, async () => {
    const categories = await req.db.models.Category.findAll({
      include: [
        {
          model: req.db.models.Product,
          attributes: ["id"],
        },
      ],
    });

    return categories;
  });
});
```
```
function numberToString(num) {
  return num.toString()
}
```

## __Experience__: 

Name | Position | Stack | Period | Projects |
-----|----------|-------|--------|--------|
*Timal Consulting Group* | **Junior Backend Developer** | *NodeJS(Express), PostgreSQL, MySQL, SQLite, Swagger, Docker* | March 2024 - March 2025 |  https://shop.plugins.smart-soft.kz/ |

***
## __Education__:

- **University**: *Kazakh-British Technical University, School of Information Technology and Engineering, Program: Computer Systems and Software.* 2023-2027
- Other courses:
    - Udemy
    - FreeCodeCamp
    - Stepik
    - CS50

***
## __Languages__:
- English - Proficient (IELTS Overall Band Score: 7.0 – C1)
- Russian - Proficient (C1)
- Kazakh - Proficient (C1)
