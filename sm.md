[Вопросы для собеседования](README.md)

# Spring MVC
+ [Что такая фреймворк `Spring MVC`?](#Что-такая-фреймворк-Spring-MVC)
+ [Какие преимущества фреймворка `Spring MVC` по сравнению с другими MVC фреймворками?](#Какие-преимущества-фреймворка-Spring-MVC-по-сравнению-с-другими-MVC-фреймворками)
+ [Что такой `DispatcherServlet` в `Spring MVC` Можете ли вы объяснить архитектуру Spring MVC?](#Что-такой-DispatcherServlet-в-Spring-MVC-Можете-ли-вы-объяснить-архитектуру-Spring-MVC)
+ [Что такой паттерн `View Resolver` и объясните его значение в `Spring MVC`?](#Что-такой-паттерн-View-Resolver-и-объясните-его-значение-в-Spring-MVC)
+ [Для чего используется аннотация `Controller`?](#Для-чего-используется-аннотация-Controller)
+ [Можно ли создать контроллер без использования аннотаций `Controller` или `RestControllerv?`](#Можно-ли-создать-контроллер-без-использования-аннотаций-Controller-или-RestController)
+ [Что такое `ContextLoaderListener` и что она делает?](#Что-такое-ContextLoaderListener-и-что-она-делает)
+ [В чем разница между аннотациями `RequestParam` и `PathVariable`?](#В-чем-разница-между-аннотациями-RequestParam-и-PathVariable)
+ [Что такое модель `Model` в Spring MVC?](#Что-такое-модель-Model-в-Spring-MVC)
+ [Для чего используется аннотация `Autowired`?](#Для-чего-используется-аннотация-Autowired)
+ [Какова роль аннотации `ModelAttribute`?](#Какова-роль-аннотации-ModelAttribute)
+ [Какова важность файла `web.xml` в `Spring MVC`?](#Какова-важность-файла-web.xml-в-Spring-MVC)
+ [Какие типы внедрения зависимостей `Dependency Injection` существуют в Spring MVC?](#Какие-типы-внедрения-зависимостей-Dependency-Injection-существуют-в-Spring-MVC)
+ [Какова важность области видимости сессии `session scope`?](#Какова-важность-области-видимости-сессии-session-scope)
+ [Каково значение аннотации `Required`?](#Каково-значение-аннотации-Required)
+ [В чем разница между аннотациями `Autowired и Inject`?](#В-чем-разница-между-аннотациями-Autowired-и-Inject)
+ [Являются ли синглтон-бины `singleton beans` потокобезопасными?](#Являются-ли-синглтон-бины-singleton-beans-потокобезопасными)
+ [Как можно обеспечить потокобезопасность в beans?](#Как-можно-обеспечить-потокобезопасность-в-beans)
+ [Каково значение аннотации `Repository`?](#Каково-значение-аннотации-Repository)
+ [Как инициализируется диспетчер сервлетов `dispatcher servlet`?](#Как-инициализируется-диспетчер-сервлетов-dispatcher-servlet)
+ [Как загружается корневой контекст приложения `root application context` в Spring MVC?](#Как-загружается-корневой-контекст-приложения-root-application-context-в-Spring-MVC)
+ [Как выглядит поток выполнения в Spring MVC Другими словами, как `DispatcherServlet` узнает, какой контроллер следует вызвать при поступлении запроса в Spring MVC?](#Как-выглядит-поток-выполнения-в-Spring-MVC-Другими-словами-как-DispatcherServlet-узнает-какой-контроллер-следует-вызвать-при-поступлении-запроса-в-Spring-MVC)
+ [Откуда происходит доступ к модели `model` из представления `view`?](#Откуда-происходит-доступ-к-модели-model-из-представления-view?)
+ [Зачем нам нужен `BindingResult`?](#Зачем-нам-нужен-BindingResult)
+ [Что такие интерцепторы `interceptors` в Spring?](#Что-такие-interceptors-в-Spring)
+ [Нужно ли находиться на classpath файлу `spring-mvc.jar` или он уже присутствует в составе `spring-core`?](#Нужно-ли-находиться-на-classpath-файлу-spring-mvc.jar-или-он-уже-присутствует-в-составе-spring-core?)
+ [В чем разница между тегами `context annotation config` и `context component scan`?](#В-чем-разница-между-тегами-context-annotation-config-и-context-component-scan)
+ [Как выполняется валидация данных формы в фреймворке `Spring Web MVC`?](#Как-выполняется-алидация-данных-формы-в-фреймворке-Spring-Web-MVC)
+ [Как получить объекты `ServletConfig` и `ServletContext` в spring bean?](#Как-получить-объекты-ServletConfig-и-ServletContext-в-spring-bean)
+ [Как в Spring MVC поддерживаются  `i18n` международная адаптация и локализация?](#Как-в-Spring-MVC-поддерживаются-i18n-международная-адаптация-и-локализация?)
+ [Что вы понимаете под `MultipartResolver`?](#Что-вы-понимаете-под-MultipartResolver)
+ [Как можно использовать источник данных `Tomcat JNDI` Tomcat JNDI DataSource в приложениях Spring?](#Как-можно-использовать-источник-данных-Tomcat-JNDI-Tomcat-JNDI-DataSource-в-приложениях-Spring?)
+ [Каково состояние выбора `checkbox`, если пользователь сначала отмечает его, получает ошибки проверки в других полях, а затем снимает отметку с checkbox после возникновения ошибок?](#Каково-состояние-выбора-checkbox-если-пользователь-сначала-отмечает-его-получает-ошибки-проверки-в-других-полях-а-затем-снимает-отметку-с-checkbox-после-возникновения-ошибок)



## Что такая фреймворк `Spring MVC`?
+ _Spring MVC_ - это фреймворк, ориентированный на обработку запросов, и является одной из основных компонент Spring Framework.
+ Он предоставляет готовые компоненты и элементы с слабой связью, которые значительно облегчают разработку гибких и надежных веб-приложений.
+ Архитектура MVC (Model - View - Controller) разделяет и обеспечивает слабую связь между различными аспектами приложения: логика ввода (Model), бизнес-логика (Controller) и логика пользовательского интерфейса (View).

[к оглавлению](#Spring-MVC)

## Какие преимущества фреймворка `Spring MVC` по сравнению с другими MVC фреймворками?
+ Ясное разделение ролей - для каждой роли существует специализированный объект.
+ Переиспользуемый бизнес-код - с помощью Spring MVC нет необходимости дублировать код. Существующие объекты могут использоваться в качестве команд вместо их репликации для расширения определенного базового класса фреймворка.
+ Фреймворк Spring MVC предоставляет настраиваемую привязку и проверку данных.
+ Также предоставляет настраиваемое разрешение локали и темы.
+ Spring MVC поддерживает настраиваемое отображение обработчиков и представлений.

[к оглавлению](#Spring-MVC)

## Что такой `DispatcherServlet` в `Spring MVC` Можете ли вы объяснить архитектуру Spring MVC?
_Фреймворк Spring MVC_ построен вокруг центрального сервлета, называемого `DispatcherServlet`, который обрабатывает все HTTP-запросы и ответы. DispatcherServlet делает намного больше:

+ Он плавно интегрируется с контейнером `IoC` и позволяет использовать все возможности Spring в более удобном виде.
+ DispatcherServlet обращается к HandlerMapping для вызова соответствующего контроллера для обработки полученного запроса. Затем контроллер вызывает соответствующие методы сервиса для установки или обработки данных Model. Сервис обрабатывает данные и возвращает имя представления DispatcherServlet. Затем DispatcherServlet с помощью ViewResolver выбирает определенное представление для запроса. Когда представление выбрано, DispatcherServlet передает данные Model в представление, которое в конечном итоге отображается в браузере.

[к оглавлению](#Spring-MVC)

## Что такой паттерн `View Resolver` и объясните его значение в `Spring MVC`?
+ Это шаблонный паттерн J2EE, который позволяет приложениям динамически выбирать технологию для отображения данных в браузере (представление).
В качестве представления можно использовать любую технологию, такую как HTML, JSP, XSLT, JSF или любую другую подобную технологию.
+ Представление Resolver содержит информацию о различных представлениях. Контроллер возвращает имя представления, которое затем передается Resolver'у DispatcherServlet для выбора соответствующей технологии представления, после чего данные отображаются.
+ В `Spring MVC` используется по умолчанию представление `InternalResourceViewResolver`.

[к оглавлению](#Spring-MVC)

## Для чего используется аннотация `Controller`?
Аннотация @Controller является стереотипной аннотацией Spring MVC для определения контроллера.

[к оглавлению](#Spring-MVC)

## Можно ли создать контроллер без использования аннотаций `Controller` или `RestControllerv?`
Да! Можно создать контроллер без аннотаций `@Controller `или `@RestController`, аннотировав классы контроллеров Spring MVC с использованием аннотации `@Component.` В этом случае реальная работа по сопоставлению запросов с методами контроллера выполняется с использованием аннотации @RequestMapping.

[к оглавлению](#Spring-MVC)

## Что такое `ContextLoaderListener` и что она делает?
+ ContextLoaderListener загружает и создает ApplicationContext, поэтому разработчику не нужно писать явный код для его создания. Кратко говоря, это слушатель, который помогает загрузить Spring MVC.

_Контекст приложения_ - это то место, где находятся бины Spring. Для веб-приложения существует подкласс, называемый WebAppliationContext.

+ Жизненный цикл ApplicationContext связан с жизненным циклом ServletContext с помощью `ContextLoaderListener. ServletContext из WebApplicationContext` можно получить с помощью метода getServletContext().

[к оглавлению](#Spring-MVC)

## В чем разница между аннотациями `RequestParam` и `PathVariable`?
- Несмотря на то, что обе эти аннотации используются для извлечения данных из URL, между ними есть ключевая разница.
+ Аннотация @RequestParam используется для извлечения параметров запроса, то есть всего, что находится после символа "?" в URL.
+ Аннотация @PathVariable используется для извлечения данных, которые являются частью самого URI.
+ Например, если заданный URL - http://localhost:8080/InterviewBit/Spring/SpringMVC/?format=json, то вы можете получить доступ к параметру запроса "format" с помощью аннотации `@RequestParam,` а /Spring/{type} - с помощью аннотации `@PathVariable`, которая даст вам значение SpringMVC.

```java
@RequestMapping("/Spring/{type}")
public void getQuestions(@PathVariable("type") String type,
@RequestParam(value = "format", required = false) String format){
/* Some code */
}
```
[к оглавлению](#Spring-MVC)

## Что такое модель `Model` в Spring MVC?
+ _Модель_ - это ссылка для получения данных для отображения.
+ Она всегда создается и передается в представление в Spring MVC. Если у метода контроллера есть параметр Model, то экземпляр модели автоматически внедряется в этот метод.
+ Любые атрибуты, установленные в модели, будут сохранены и переданы в представление.

[к оглавлению](#Spring-MVC)

## Для чего используется аннотация `Autowired`?
Аннотация `@Autowired` предназначена для внедрения бина по его типу вместе с методами и полями. Это помогает Spring Framework разрешать зависимости, внедряя и сотрудничая бины в другой бин. Например, рассмотрим следующий фрагмент кода:

```java
import org.springframework.beans.factory.annotation.Autowired;
import java.util.*;

public class InterviewBit {
// Внедрение/инъекция FormatterUtil в качестве зависимости для класса InterviewBit
@Autowired
private FormatterUtil formatterUtil;

public Date something( String value ){
Date dateFormatted = formatterUtil.formatDate(value);
return dateFormatted
}
}

/**

Утилитарный класс для форматирования строки в допустимый формат даты
*/
public class FormatterUtil {

public Date formatDate(String value){
//код для форматирования даты
}
}
```

[к оглавлению](#Spring-MVC)

## Какова роль аннотации `ModelAttribute`?
Аннотация играет очень важную роль в привязке параметров метода к соответствующему атрибуту модели, который соответствует модели. Затем это отражается на странице представления. Роль аннотации также зависит от того, для чего ее использует разработчик. Если она используется на уровне метода, то этот метод отвечает за добавление атрибутов в модель. Если используется на уровне параметра, это означает, что значение параметра должно быть получено из модели.

[к оглавлению](#Spring-MVC)

## Какова важность файла `web.xml` в `Spring MVC`?
web.xml, также известный как Deployment Descriptor, содержит определения сервлетов и их сопоставления, фильтры и прослушиватели жизненного цикла. Он также используется для конфигурации ContextLoaderListener. При развертывании приложения создается экземпляр ContextLoaderListener контейнером сервлетов, что приводит к загрузке WebApplicationContext.

[к оглавлению](#Spring-MVC)

## Какие типы внедрения зависимостей `Dependency Injection` существуют в Spring MVC?
_Существуют два типа внедрения зависимостей (Dependency Injection) в Spring MVC:_

- Основанный на конструкторе:
	+ Этот тип внедрения зависимостей реализуется, когда контейнер `Spring IoC` (Inversion of Control) вызывает параметризованный конструктор, который зависит от других классов.
	+ Он не может частично инициализировать значения и гарантирует полное внедрение зависимостей.
	+ Существуют два способа достижения этого:
_Конфигурация через аннотации:_ В этом подходе используются POJO-объекты и аннотации для конфигурации. Например, рассмотрим следующий фрагмент кода:

```java
@Configuration
@ComponentScan("com.interviewbit.constructordi")
public class SpringAppConfig {
@Bean
public Shape shapes() {
return new Shapes("Rectangle");
}
@Bean
public Dimension dimensions() {
return new Dimension(4,3);
}
}
```

Здесь аннотации используются для уведомления Spring о том, что класс, указанный с аннотацией @Bean, является поставщиком бинов, и что необходимо выполнить процесс сканирования контекста в пакете com.interviewbit.constructordi с помощью аннотации @ComponentScan. Затем мы определим компонент класса Figure следующим образом:

```java
@Component
public class Figure {
private Shape shape;
private Dimension dimension;

@Autowired
public Figure(Shape shape, Dimension dimension) {
this.shape = shape;
this.dimension = dimension;
}
}
```

Spring встречает этот класс Figure при выполнении сканирования контекста и инициализирует экземпляр этого класса, вызывая конструктор, помеченный аннотацией @Autowired. Экземпляры Shape и Dimension получаются путем вызова методов, помеченных аннотацией @Bean в классе SpringAppConfig. Экземпляры Engine и Transmission получаются путем вызова методов, помеченных аннотацией @Bean в классе Config. Наконец, нам нужно создать ApplicationContext с использованием нашей конфигурации POJO:

```java
ApplicationContext context = new AnnotationConfigApplicationContext(SpringAppConfig.class);
Figure figure = context.getBean(Figure.class);
```
_Конфигурация через XML:_ Еще один способ конфигурации Spring с использованием файла XML-конфигурации. Например, рассмотрим следующий фрагмент кода в файле springAppConfig.xml:

```xml
<bean id="toyota" class="com.interviewbit.constructordi.Figure">
   <constructor-arg index="0" ref="shape"/>
   <constructor-arg index="1" ref="dimension"/>
</bean>
<bean id="shape" class="com.interviewbit.constructordi.Shape">
   <constructor-arg index="0" value="Rectangle"/>
</bean>
<bean id="dimension" class="com.interviewbit.constructordi.Dimension">
   <constructor-arg index="0" value="4"/>
   <constructor-arg index="1" value="3"/>
</bean>
```

Тег constructor-arg может принимать либо литеральное значение, либо ссылку на другой бин, а также явно указывать индекс и тип. Индекс и тип используются для разрешения конфликтов в случае неоднозначности.
При инициализации этого класса Spring ApplicationContext должен использовать ClassPathXmlApplicationContext, как показано ниже:

```java
ApplicationContext context = new ClassPathXmlApplicationContext("springAppConfig.xml");
Figure figure = context.getBean(Figure.class);
```

_Основанный на сеттере:_
Этот тип внедрения зависимостей осуществляется, когда контейнер Spring IoC вызывает сеттер (метод установки) бина после вызова конструктора без параметров для создания объекта бина.
Внедрение зависимостей через сеттер позволяет реализовать круговые зависимости.
Для достижения этого типа внедрения зависимостей необходимо настроить его через файл конфигурации внутри тега <property>. Например, рассмотрим класс InterviewBit, который устанавливает свойство articles следующим образом:

```java
package com.interviewbit.model;
import com.interviewbit.model.Article;
public class InterviewBit {
// Объект интерфейса Article
Article article;
public void setArticle(Article article)
{
this.article = article;
}
}
```

В файле конфигурации бинов мы зададим следующее:

```xml
<beans xmlns="http://www.springframework.org/schema/beans" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" xsi:schemaLocation="http://www.springframework.org/schema/beans http://www.springframework.org/schema/beans/spring-beans-2.5.xsd">
   <bean id="InterviewBit" class="com.interviewbit.model.InterviewBit">
       <property name="article">
           <ref bean="JsonArticle" />
       </property>
   </bean>
   <bean id="JsonArticle" class="com.interviewbit.bean.JsonArticle" />
</beans>
```
Бин "JsonArticle" внедряется в объект класса InterviewBit с помощью метода setArticle.
В случаях, когда используются оба типа зависимостей, внедрение зависимостей через сеттер имеет более высокий приоритет, учитывая специфичность данного подхода.

[к оглавлению](#Spring-MVC)

## Какова важность области видимости сессии `session scope`?
Область сессии используется для создания экземпляров бинов для HTTP-сессий. Это означает, что один и тот же бин может использоваться для обработки нескольких HTTP-запросов. Область бина может быть определена с использованием атрибута scope, а также с использованием аннотаций @Scope или @SessionScope.

Использование атрибута scope:
<bean id="userBean" class="com.interviewbit.UserBean" scope="session"/>
Использование аннотации @Scope:

```java
@Component
@Scope("session")
public class UserBean {
//некоторые методы и свойства
}
```
Использование аннотации @SessionScope:

```java
@Component
@SessionScope
public class UserBean {
//некоторые методы и свойства
}
```
[к оглавлению](#Spring-MVC)

## Каково значение аннотации `Required`?
Аннотация @Required используется для указания, что свойство бина должно быть заполнено с помощью автоматической инъекции или явного значения во время определения бина при конфигурации. Например, рассмотрим следующий фрагмент кода, где необходимо иметь значения для полей age и name:

```java
import org.springframework.beans.factory.annotation.Required;
public class User {
private int age;
private String name;

@Required
public void setAge(int age) {
this.age = age;
}
public Integer getAge() {
return this.age;
}

@Required
public void setName(String name) {
this.name = name;
}
public String getName() {
return this.name;
}
}
```

[к оглавлению](#Spring-MVC)

## В чем разница между аннотациями `Autowired и Inject`?
+ `@Autowired` является частью фреймворка Spring, в то время как `@Inject` является частью Java CDI.
+ @Autowired имеет атрибут required, в то время как @Inject не имеет такого атрибута.
+ По умолчанию для бинов с аннотацией @Autowired используется область видимости singleton. Для бинов с аннотацией @Inject область видимости по умолчанию - prototype.
+ В случае неоднозначности в аннотации @Autowired используется аннотация @Qualifier. В случае неоднозначности в аннотации @Inject используется аннотация @Named.
+ Поскольку аннотация @Autowired предоставляется фреймворком Spring, при смене фреймворка DI потребуется много переработки кода. Аннотация @Inject является частью Java CDI и не зависит от конкретного фреймворка, поэтому при изменении фреймворка потребуется меньше изменений кода.

[к оглавлению](#Spring-MVC)

## Являются ли синглтон-бины `singleton beans` потокобезопасными?
Нет, синглтон-бины не являются потокобезопасными, поскольку понятие потокобезопасности относится к выполнению программы, а синглтон - это просто шаблонконфигурации для создания одного экземпляра бина в контейнере Spring. Если необходима потокобезопасность, нужно предпринять дополнительные меры, такие как синхронизация доступа к ресурсам или использование других механизмов управления потоками.

[к оглавлению](#Spring-MVC)

## Как можно обеспечить потокобезопасность в бинах (beans)?
Для обеспечения потокобезопасности в бинах можно изменить область видимости бина на request, session или prototype, но это может сказаться на производительности. Это полностью зависит от требований проекта.

[к оглавлению](#Spring-MVC)

## Каково значение аннотации `Repository`?
Аннотация @Repository указывает, что компонент используется в качестве репозитория, который служит для хранения, поиска или извлечения данных. Она может быть применена к классам DAO.

[к оглавлению](#Spring-MVC)

## Как инициализируется диспетчер сервлетов `dispatcher servlet`?
Диспетчерский сервлет создается с помощью сервлет-контейнеров, таких как Tomcat. Диспетчерский сервлет должен быть определен в файле web.xml. Диспетчерский сервлет создается сервлет-контейнерами, такими как Tomcat. Диспетчерский сервлет может быть определен в файле web.xml, как показано ниже:

```xml
<?xml version="1.0" encoding="UTF-8"?>
<web-app version="2.5" xmlns="http://java.sun.com/xml/ns/javaee" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"
xsi:schemaLocation="http://java.sun.com/xml/ns/javaee http://java.sun.com/xml/ns/javaee/web-app_2_5.xsd">


 <!-- Определение диспетчерского сервлета -->
 <servlet>
   <servlet-name>appServlet</servlet-name>
   <servlet-class>org.springframework.web.servlet.DispatcherServlet</servlet-class>
   <init-param>
     <param-name>contextConfigLocation</param-name>
     <param-value>/WEB-INF/spring/appServlet/servlet-context.xml</param-value>
   </init-param>
   <load-on-startup>1</load-on-startup>
 </servlet>
 <servlet-mapping>
   <servlet-name>InterviewBitServlet</servlet-name>
   <url-pattern>/</url-pattern>
 </servlet-mapping>
</web-app>
```

Здесь тег load-on-startup имеет значение 1, что означает, что диспетчерский сервлет создается каждый раз, когда приложение Spring MVC развертывается в сервлет-контейнере. При этом происходит поиск файла servlet-name-context.xml и инициализация определенных в нем бинов.


[к оглавлению](#Spring-MVC)

## Как загружается корневой контекст приложения `root application context` в Spring MVC?
Контекст корневого приложения загружается с помощью ContextLoaderListener, который принадлежит всему приложению. Spring MVC позволяет создавать несколько диспетчерских сервлетов, и каждый из них может иметь свои собственные контексты. Они также могут использовать один и тот же корневой контекст.

[к оглавлению](#Spring-MVC)

## Как выглядит поток выполнения в Spring MVC Другими словами, как `DispatcherServlet` узнает, какой контроллер следует вызвать при поступлении запроса в Spring MVC?
Диспетчерский сервлет определяет, какой контроллер вызвать с помощью механизма обработчиков (handler mappings). Эти обработчики имеют соответствие между контроллерами и запросами. Самые часто используемые обработчики - это BeanNameUrlHandlerMapping и SimpleUrlHandlerMapping.

+ BeanNameUrlHandlerMapping: Когда URL-запрос совпадает с именем бина, класс, соответствующий определению бина, является фактическим контроллером, ответственным за обработку запроса.
+ SimpleUrlHandlerMapping: Здесь соответствие очень явное. Здесь можно указать количество URL-адресов, и каждый URL-адрес явно связывается с контроллером.
Если Spring MVC настроен с использованием аннотаций, то для этой цели используются аннотации @RequestMapping. Аннотация @RequestMapping настраивается с использованием пути URI, HTTP-методов, параметров запроса и HTTP-заголовков.

[к оглавлению](#Spring-MVC)


## Откуда происходит доступ к модели `model` из представления `(view)`?
Представлению требуется доступ к модели для визуализации вывода, так как модель содержит необходимые данные для визуализации. Модель связана с контроллером, который обрабатывает запросы клиента и в конечном итоге инкапсулирует ответ в объект Model.

[к оглавлению](#Spring-MVC)

## Зачем нам нужен `BindingResult`?
`BindingResults` - это важный интерфейс Spring, находящийся в пакете `org.Springframework.validation.` Этот интерфейс имеет очень простой и удобный процесс вызова и играет важную роль в обнаружении ошибок в отправленных формах. Однако разработчику следует обратить внимание на использование параметра BindingResult непосредственно после объекта, который требует проверки. Например:

```java
@PostMapping("/interviewbit")
public String registerCourse(@Valid RegisterUser registerUser,
BindingResult bindingResult, Model model) {
if (bindingResult.hasErrors()) {
return "home";
}
model.addAttribute("message", "Valid inputs");
return "home";
}
```
Spring будет искать соответствующие валидаторы, проверяя аннотацию @Valid для параметра.

[к оглавлению](#Spring-MVC)

## Что такие интерцепторы `interceptors` в Spring?
`Spring Interceptors` используются для предварительной и постобработки веб-запросов в Spring MVC, которые обрабатяются контроллерами Spring. Это может быть достигнуто с помощью интерфейса HandlerInterceptor. Эти обработчики используются для манипулирования атрибутами модели, которые передаются контроллерам или представлениям.
Spring handler interceptor может быть зарегистрирован для конкретных URL-сопоставлений, чтобы он мог перехватывать только эти запросы. Пользовательский обработчик-перехватчик должен реализовывать интерфейс HandlerInterceptor, который имеет 3 метода обратного вызова, которые могут быть реализованы:

+ preHandle()
+ postHandle()
+ afterCompletion()
Единственная проблема с этим интерфейсом заключается в том, что все методы этого интерфейса должны быть реализованы независимо от их требований. Это можно избежать, если наш класс обработчика расширяет класс HandlerInterceptorAdapter, который внутренне реализует интерфейс HandlerInterceptor и предоставляет пустые реализации по умолчанию.

[к оглавлению](#Spring-MVC)

## Нужно ли находиться на classpath файлу `spring-mvc.jar` или он уже присутствует в составе `spring-core`?
`spring-mvc.jar` не принадлежит к spring-core. Это означает, что jar-файл должен быть включен в classpath проекта, если мы хотим использовать фреймворк Spring MVC. Для Java-приложений spring-mvc.jar размещается в папке /WEB-INF/lib.

[к оглавлению](#Spring-MVC)

## В чем разница между тегами `context annotation config` и `context component scan`?
context:annotation-config используется для активации примененных аннотаций в предварительно зарегистрированных бинах в контексте приложения. Он также регистрирует бины, определенные в файле конфигурации, и сканирует аннотации внутри бинов и активирует их.

Тег context:component-scan выполняет задачу context:annotation-config, а также сканирует пакеты и регистрирует бины в контексте приложения.

context:annotation-config = Сканировать и активировать аннотации в предварительно зарегистрированных бинах.
context:component-scan = Регистрация бина + Сканирование и активация аннотаций в пакете.

[к оглавлению](#Spring-MVC)

## Как выполняется валидация данных формы в фреймворке `Spring Web MVC`?
`Spring MVC` выполняет проверку данных с использованием объекта валидатора, который реализует интерфейс Validator. В пользовательском классе валидатора, который мы создали, мы можем использовать вспомогательные методы класса ValidationUtils, такие как rejectIfEmptyOrWhitespace() или rejectIfEmpty(), для выполнения проверки полей формы.

```java
@Component
public class UserValidator implements Validator
{
public boolean supports(Class clazz) {
return UserVO.class.isAssignableFrom(clazz);
}

public void validate(Object target, Errors errors)
{
ValidationUtils.rejectIfEmptyOrWhitespace(errors, "name", "error.name", "Name is required.");
ValidationUtils.rejectIfEmptyOrWhitespace(errors, "age", "error.age", "Age is required.");
ValidationUtils.rejectIfEmptyOrWhitespace(errors, "phone", "error.phone", "Phone is required.");
}
}
```
В полях, подлежащих проверке, в случае ошибок методы валидатора создадут ошибку поля и привяжут ее к полю.

Чтобы активировать пользовательский валидатор в качестве Spring-бина, необходимо:

Добавить аннотацию @Component на пользовательский класс валидатора и запустить сканирование компонентов пакета, содержащего объявления валидатора, добавив следующие изменения:
<context:component-scan base-package="com.interviewbit.validators"/>
ИЛИ

Класс валидатора можно зарегистрировать в файле контекста непосредственно как бин, как показано ниже:

```xml
<bean id="userValidator" class="com.interviewbit.validators.UserValidator" />
```

[к оглавлению](#Spring-MVC)


## Как получить объекты `ServletConfig` и `ServletContext` в spring bean?
Это можно сделать, либо реализовав интерфейсы, связанные с Spring, либо используя аннотацию `@Autowired`.

```java
@Autowired
private ServletContext servletContext;
@Autowired
private ServletConfig servletConfig;
```

[к оглавлению](#Spring-MVC)


## Как в Spring MVC поддерживаются  `i18n` международная адаптация и локализация?
Spring MVC имеет LocaleResolver, который поддерживает i18n и локализацию. Для поддержки международной и локализации необходимо настроить следующие бины в приложении:

_SessionLocaleResolver:_ Этот бин играет важную роль в получении и разрешении локалей из предопределенных атрибутов в сеансе пользователя.
Синтаксис:
```xml
<bean id="localeResolver" class="org.springframework.web.servlet.i18n.SessionLocaleResolver">
   <property name="defaultLocale" value="en" />
</bean>
```
_LocaleChangeInterceptor:_ Этот бин используется для разрешения параметра из входящего запроса.
Синтаксис:

```xml
<bean id="localeChangeInterceptor" class="org.springframework.web.servlet.i18n.LocaleChangeInterceptor">
   <property name="paramName" value="lang" />
</bean>
```
_DefaultAnnotationHandlerMapping:_ Это относится к реализации интерфейса HandlerMapping, который отображает обработчики/интерцепторы на основе HTTP-путей, указанных в аннотации @RequestMapping на уровне типа или метода.
Синтаксис:

```xml
<bean class="org.springframework.web.servlet.mvc.annotation.DefaultAnnotationHandlerMapping">
   <property name="interceptors">
       <list>
           <ref bean="localeChangeInterceptor" />
       </list>
   </property>
</bean>
```
[к оглавлению](#Spring-MVC)

## Что вы понимаете под `MultipartResolver`?
`MultipartResolver` используется для обработки сценариев загрузки файлов в веб-приложении Spring. В Spring есть 2 конкретные реализации этого интерфейса:

+ CommonsMultipartResolver предназначен для Jakarta Commons FileUpload.
+ StandardServletMultipartResolver предназначен для использования Servlet 3.0 Part API.
Для реализации этого необходимо создать бин с идентификатором "multipartResolver" в контексте приложения DispatcherServlet. Таким образом, все запросы, обрабатываемые DispatcherServlet, будут иметь этот разрешитель, применяемый при обнаружении многоканального запроса. Если DispatcherServlet обнаруживает многоканальный запрос, он разрешает запрос с помощью уже настроенного MultipartResolver, и запрос передается как обернутый/абстрактный HttpServletRequest. Затем контроллеры приводят этот запрос к интерфейсу MultipartHttpServletRequest, чтобы получить доступ к многоканальным файлам. Следующая диаграмма наглядно иллюстрирует этот процесс:

[к оглавлению](#Spring-MVC)

## Как можно использовать источник данных `Tomcat JNDI` Tomcat JNDI DataSource в приложениях Spring?
Для использования источника данных Tomcat, настроенного в JNDI (Java Naming and Directory Interface), необходимо настроить бин DataSource в файле конфигурации Spring и затем внедрить его в бины в качестве зависимостей. После этого бин DataSource может быть использован для выполнения операций с базой данных с помощью JdbcTemplate. Синтаксис для регистрации бина DataSource для MySQL:

```xml
<bean id="dataSource" class="org.springframework.jndi.JndiObjectFactoryBean">
   <property name="jndiName" value="java:comp/env/jdbc/MySQLDB"/>
</bean>
```
[к оглавлению](#Spring-MVC)

## Каково состояние выбора `checkbox`, если пользователь сначала отмечает его, получает ошибки проверки в других полях, а затем снимает отметку с checkbox после возникновения ошибок?
Обычно проверка выполняется во время запросов HTTP POST. Во время HTTP-запросов, если состояние элемента checkbox не установлено, то HTTP не включает параметр запроса для элемента checkbox и не учитывает обновленное состояние. Это можно исправить, используя скрытое поле формы, начинающееся с символа "_" в Spring MVC.

[к оглавлению](#Spring-MVC)




