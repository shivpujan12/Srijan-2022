# ART of Android

---

| Question   | Answer                                                            |
| ---------- | ----------------------------------------------------------------- |
| Writer     | SHIVPUJAN YADAV - MCA I year |
| Editor     | RITIK SONI |
| Status     | Edited |
| Plagiarism | 0% [Report](https://github.com/RishPoria/Srijan-2021/blob/f6d16deca3319ea1383e2ff90ec63b868063407b/articles/plagReports/CelestialAI.pdf)|

---

## Introduction

ART acronym of Android Run Time is current processing virtual machines in the Android Software Stack. It is the Runtime Virtual Machine which sits above the Hardware Abstraction Layer to process the High-Level Language byte code to the Machine Language that Android understands. It is used to execute the applications written on Android. So, you can see ART as the ART of Android to execute the applications on the Android Platform by using less battery, and runtime memory. It is the ART of android to talk in Machine Language.

## History

ART is a new and latest android runtime being introduced as a beta in Android KitKat and finally became an integral part of the Android Software Stack for later versions and versions of Android Lollipop. So, if the Android Runtime was introduced in Android KitKat then how were the applications executed in the older versions of Android? – The answer is Dalvik.

## Dalvik’s Android Era

What is Dalvik? -Dalvik is the Android processing Virtual Machine which was used to execute the applications on the Android Versions older than Android KitKat 4.4 release. Dalvik is the ancestor of ART hence the byte code of application designed for Dalvik is also compatible with the ART, hence ART supports backward compatibility. Dalvik was developed by Dan Bornstein and has origins in a town in Iceland named Dalvik, hence the name of the virtual machine originated from that town.

## Dalvik’s Architecture

Dalvik is a Just in Time Compiler (JIT) – JIT means that whenever the compiler executes the application code, it only compiles the required code that is needed at that moment and the rest of the code is compiled later whenever required. Since it compiles only a part of the code it has a smaller memory footprint and hence it makes use of less physical memory on the device, which increases the performance of the device. Since everything in Android Mobile phones is limited whether it be the battery life, processing and memory etc. Dalvik Virtual Machine (DVM) optimizes the code so that it can fit in low powered devices. Programs for Android are mainly written and processed in java which is compiled to Java Bytecode for JVM and then translated to. dex (Dalvik Executable) or. odex (Optimized Dalvik Executable) format which is understood by Dalvik and executed by DVM in low powered mobile devices.

