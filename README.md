## 前言

感谢您对"船舶监造系统"项目的关注。本项目是一款基于Java和MySQL开发的管理系统，适用于船舶监造领域。通过本系统，用户可以方便地管理船舶监造的相关信息，提高工作效率。本文将详细介绍本项目的相关内容，帮助您更好地了解和使用本系统。

## 内容介绍

船舶监造系统是一款针对船舶监造行业的在线管理系统。该系统提供了丰富的功能，包括项目管理、进度跟踪、质量检验、物料管理、生产调度以及成本控制等，能够全面覆盖造船业务流程，实现船舶监造的信息化管理。每一个功能都经过严格的测试，确保系统的稳定性和可用性。用户下载后无需任何修改即可直接运行。

## 技术介绍

- **语言**：Java
- **使用框架**：Spring Boot
- **前端技术**：JS、Vue、css3
- **开发工具**：IDEA/Eclipse
- **数据库**：MySQL 5.7/8.0
- **数据库管理工具**：phpstudy/Navicat
- **JDK版本**：jdk1.8
- **Maven**：apache-maven 3.8.1-bin
- **前端环境**：Node.Js 12\14\16

## 核心代码

```java
@RestController
@RequestMapping("/project")
public class ProjectController {

    @Autowired
    private ProjectService projectService;

    @GetMapping("/list")
    public List<Project> list() {
        return projectService.list();
    }

    @GetMapping("/get/{id}")
    public Project get(@PathVariable("id") Long id) {
        return projectService.get(id);
    }

    @PostMapping("/add")
    public void add(@RequestBody Project project) {
        projectService.add(project);
    }

    @PutMapping("/update")
    public void update(@RequestBody Project project) {
        projectService.update(project);
    }

    @DeleteMapping("/delete/{id}")
    public void delete(@PathVariable("id") Long id) {
        projectService.delete(id);
    }
}
```

## 免费源码获取

```
8000套系统成品在线演示视频，复制到流浪器： 
```
```
https://www.yuque.com/yuqueyonghux32e1j/kxdc9g/ad8oz3bamkxmay0e#Cxun
```
![下载](https://img12.360buyimg.com/ddimg/jfs/t1/339687/11/1349/28408/68ad865fF412d7877/adaa650483a100f2.jpg)

# 项目截图

![封面图片](https://img11.360buyimg.com/ddimg/jfs/t1/308857/23/26469/141847/689e0ff1F0b599f8d/738a3453c9ce6208.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/312859/5/26341/84205/689e0fd0F9007ccb2/5da43205cad859c1.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/313301/5/26282/86014/689e0fd0Fbd5fd701/7d745860b4fd442e.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/291537/4/22012/38124/689e0fd1F8342f6b8/c99dd9ea7a016308.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/317276/13/24923/84625/689e0fd2F8e974f16/baebe71e3e4369fe.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/308588/17/26526/42376/689e0fd2Fac44b6cc/868f75a69be34fe0.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/317438/22/25236/53549/689e0fd3F034b844e/72fb988193902872.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/317032/29/25675/50839/689e0fd4F9c215b0b/16171acef5ca6ae0.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/313080/33/26532/40550/689e0fd4F5ae1a235/91b6b72d794f4035.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/309991/16/26545/41478/689e0fd5Fedcdad54/d130ee7f7cbfce30.jpg)


## 万字文档
![文档介绍](https://img14.360buyimg.com/ddimg/jfs/t1/338393/1/3576/156947/68b1ad0cF74dc525c/ff9cd6c574295685.jpg)
