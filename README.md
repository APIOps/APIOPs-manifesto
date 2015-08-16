# APIOPs 
* [APIOPs manifesto v1](https://github.com/APIOps/APIOPs-manifesto/blob/master/manifesto_v1.md)

##Introduction
McKinsey Global Institute estimates the potential economic impact of the Internet of Things to be $2.7 trillion to $6.2 trillion per year by 2025.  The GSM Association predicts that by 2020, there will be 24 billion connected devices, while Cisco’s Internet of Everything prediction is 50 billion “intelligent things,” such as cars,  appliances, smartphones, tablets, monitoring sensors and more, connected  to the Internet. The rise of IoT depends on a whole host of enabling technologies like  RFID, IPv6, Big Data, and Application Programming Interfaces (APIs). Web APIs, or more specifically REST APIs, are key for connecting devices to the Internet.

A large part of the interoperability, scale, and control for IoT can be achieved through API management.  Standards-based  design patterns for Web APIs, API management, and a  RESTful  architecture provide tremendous value in simplifying the task  of  interoperability across heterogeneous systems handling vast amounts  of  data. Since APIs have become ubiquitous, IoT deployments spanning a  wide  range of market segments can benefit from this proven  architecture.

```
Companies focusing on enabling fast API development together with customers 
and nearby interest groups will rule the IoT.
```

Industrial Internet, Internet of Everything, Internet of Things (IoT) and Industrie 4.0 are the terms which are brought up more and more in articles and discussions when it comes to future and the visions for it. IoT is driven by the power and speed of APIs. IoT is often discussed in the context of industry mostly because that is where it will first create biggest changes. However, to understand more clearly what IoT is we should take imagine what it could be in the everyday life of citizens. 

In everyday life IoT can be rather simple things. For example your coffee maker is connected to your alarm clock and no matter what time up the alarm goes off, coffee is brewed. Your colleagues at work can be notified of your possible delay because of possible traffic jams on your way to office. Your home automation can shut the lights and adjust  temperature when everyone is away. According to Samsung in 2020, every device Samsung sells world wide will be connected to the Internet of Things. Since leading manufacturers of our digital devices have such goals, it is no wonder that Gartner predicts that there will be nearly 26 billion devices on the Internet of Things by 2020. Eventually it means that even our living room chairs are connected to IoT and exchange information with other devices. Our living room it self could be connected to tv and according to noise level adjust the volume to be just perfect. This also gives us opportunities to use surfaces as interfaces. For example we could use ordinary windows made of glass as email app interface. Or we could watch morning news from the mirror while brushing teeth.

International Organization for Standardization is well known and established standardization body and their definition of IoT is as follows: 

```
An infrastructure of interconnected objects, people, systems and 
information resources together with intelligent services to allow them 
to process information of the physical and the virtual world and react.
``` 

Just  like DevOps can be seen as offspring or spinoff of Agile thinking,  APIOps can be seen to extend DevOps to fulfil the needs of Application  Interface and Internet of Things development (IoT).  Therefore I foresee clear need for APIOps, a new breed of DevOps to support creation and maintence of IoT driven ecosystem. 

**Practitioners of APIOps principles and values are the builders of the future.**  

![API life cycle](https://raw.githubusercontent.com/APIOps/APIOPs-manifesto/master/images/apiops-design-first.png)

Practitioners of APIOps principles and values are the builders of the future.  

##Joint open design process

API design first approach focuses on involving service and API developers and marketing to same process of co-creating API description. API description is a communication tool, it is not code, at best it is browser-based graphical userface in which all participants collaborate and contribute. Process involves 3rd party service developers into the development since they are endusers of APIs and know best the needs. Obviously the product owner of service utlizing APIs is involved. During the process all work together; sometimes intensively and occasionally there might be total silence. The  team uses f2f meetigns and online environments as well as instant messaging tools to communicate. In other words, there is no written rule or need to necessary to be all the time in the  space/room. This phase produces shared version controlled understanding of:

* API features
* API consumer needs
* Machine readable description of API or multiple APIs

##Speed up development with code generation

In the  second phase APIOps (API developer) uses the machine readable  description file to configure code generation toolchain. Toolchain automatically generates both API server skeleton and client side development kits (SDK) for plethora of operating systems including mobile platforms such as iOS, Android, Windows. 
Generating API server code kicks the development at fullspeed right from the start. API developer needs to adjust and finetune actual code a lot less compared to other approaches. The SDKs are important since they lower the barrier to utilize newly created APIs. Having top knotch API is nice, but widely utilized and liked API is golden. 

##Service Development Platform as online hub

Eventually API server code is launched at production server and attached to API management, which is part of Developer Portal (DP). DP enables service developers' easy access to APIs, API documentation, SDKs, code examples and community. In Developer Portal  API provider can limit the usage of APIs, see metrics and even retire entire API. In portal, API developers and consumers can exchange ideas and use documented comments as feedback for the next cycle which begins from the Joint open design process.  

All this should take plane inside planned roadmap and business plan. Internet of Things (IoT) is something  which in common terms connects devices to each other to exchange data.  IoT relies heavily on web APIs which in fact enable us to connect  services and objects with each other. Without reliable, easily  implemented backends and frontend support, new services build on top of  IoT, will not succeed. 



##APIOps is not...
* A role
* A set of tools
* A prescriptive process

##APIOps is...
* A philosophy that starts with passion
* A cultural, professional movement with attitude and values
* About creating visibility between API providers and consumers
* About the symbiotic relationship API providers and consumers
* Cross-functional teams over organizational silos
* Products not projects
* Automation over documentation
* About creating self-service infrastructure for API consumers
* API that doesn't require support
* Ensuring a continual feedback loop between API providers and consumers
* Knowing that a API is only finished when it is retired from production
* Something you can do without doing agile
