# Introduction
- [x] Task 1
  * Create all 8 issues, so that members can pick the issues they want to solve and complete it
- [x] Task 2
  * Create project board, so members can see which tasks is not completed, in progress and completed
- [x] Task 3
  * Create readme.md about all the issues containing brief description of each task
- [x] Task 4
  * Edit the readme.md (on the contributor section)
  * Arrange the contents into the format specified in task 4
- [ ] Task 5
  * Check whether the issues are labelle
  * Check if pull request is in proper columns
  * Remind people to include .md file in the __stu folder and their "hello" card in the project board
- [ ] Task 6
  * In code.c, write a simple C code
  * Set up a github action with a workflow to run the c code
- [ ] Task 7
  * Edit the readme.md (on the code section) and include the code from *`code.c`* (task 6) using `include_relative`
  * Highlight the code using C syntax 
  * Earn a workflow status badge for the code
  * Insert the image using markdown (under the code snippet)
- [ ] Task 8
  * Promote this repo! 
  * Request review from @chuckjee

# Code

# Contributors
{% for stu in site.stu %}    
- ![Image of Contributors]({{stu.image}} =50x50)
<a href="github.com/{{stu.user}}">
@{{stu.user}}
</a>
({{ stu.name }})
  - <p>{{ stu.content | markdownify }}</p>
{% endfor %}
