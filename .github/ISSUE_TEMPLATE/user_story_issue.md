---
name: User Story
about: Create a user story issue
---

# Parent Issue
Issue #xxx *(link the issue by replacing xxx with the issue number)*

# Priority
P1(Must have) / P2(Should have) / P3(Could have) / P4(Won't have)

# Description

> US 的描述要符合 INVEST 原则
>
> Hints: "As a Role, I want to Action, so that benefit"
>   - Independent (of all others) 独立的: 
>   - Negotiable (not a specific contract for features) 可协商的: 
>   - Valuable (or vertical) 有价值的： 
>   - Estimable (to a good approximation) 可估量的： 
>   - Small (so as to fit within an iteration) 足够小的
>   - Testable (in principle, even if there isn't a test for it yet) 可测试的

* XXXXXXXX
* XXXXXXXX
* XXXXXXXX

# DoD (Definition of Done)

- 完成设计文档
- 代码更改要创建相应的 git pull request ，并由团队成员 review 和 approve ，测试无误后合并到主开发分支
- merge request 关联到 user story 的 issue 上
- 代码更改要有相应的测试用例和测试结果 (Unit testing, API testing or manual testing)
- 代码实现符合详细设计和上述描述要求，没有严重 bug，通过 Acceptance Test Case