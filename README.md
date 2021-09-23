# following-java

이 문서는 자바가 벌써 LTS 버전인 JDK17이 릴리즈 되어서 자바 변경내용들을 공부 하기 위한 목적으로 만들었습니다.<br> 
내용은 주관적으로 나눈 분류-와 버전별로 정렬을 하여 관심있는 내용부터 확인 할 수 있도록 했습니다.


## Index
*OpenJDK [JEP Index](https://openjdk.java.net/jeps/0)를 참고하여 구성*

### Language Spec
- JDK12
    - [325_Switch Expressions (Preview)](https://openjdk.java.net/jeps/325)
- JDK13
    - [354_Switch Expressions (Second Preview)](https://openjdk.java.net/jeps/354)
    - [355_Text Blocks (Preview)](https://openjdk.java.net/jeps/355)
- JDK14
    - [305_Pattern Matching for instanceof (Preview)](https://openjdk.java.net/jeps/305)
    - [358_Helpful NullPointerExceptions](https://openjdk.java.net/jeps/358)
    - [359_Records (Preview)](https://openjdk.java.net/jeps/359)
    - [361_Switch Expressions](https://openjdk.java.net/jeps/361)
    - [368_Text Blocks (Second Preview)](https://openjdk.java.net/jeps/368)
- JDK15
    - [360_Sealed Classes (Preview)](https://openjdk.java.net/jeps/360)
    - [371_Hidden Classes](https://openjdk.java.net/jeps/371)
    - [375_Pattern Matching for instanceof (Second Preview)](https://openjdk.java.net/jeps/375)
    - [378_Text Blocks](https://openjdk.java.net/jeps/378)
    - [384_Records (Second Preview)](https://openjdk.java.net/jeps/384)
- JDK16
    - [338_Vector API (Incubator)](https://openjdk.java.net/jeps/338)
    - [394_Pattern Matching for instanceof](https://openjdk.java.net/jeps/394)
    - [395_Records](https://openjdk.java.net/jeps/395)
- JDK16
    - [397_Sealed Classes (Second Preview)](https://openjdk.java.net/jeps/397)
- JDK17 
    - [306_Restore Always-Strict Floating-Point Semantics](https://openjdk.java.net/jeps/306)
    - [406_Pattern Matching for switch (Preview)](https://openjdk.java.net/jeps/406)
    - [409_Sealed Classes](https://openjdk.java.net/jeps/409)

### GC
- JDK12
    - [189_Shenandoah: A Low-Pause-Time Garbage Collector (Experimental)](https://openjdk.java.net/jeps/189)
    - [344_Abortable Mixed Collections for G1](https://openjdk.java.net/jeps/344)
    - [346_Promptly Return Unused Committed Memory from G1](https://openjdk.java.net/jeps/346)
- JDK13
    - [351_ZGC: Uncommit Unused Memory (Experimental)](https://openjdk.java.net/jeps/351)
- JDK14
    - [345_NUMA-Aware Memory Allocation for G1](https://openjdk.java.net/jeps/345)
    - [363_Remove the Concurrent Mark Sweep (CMS) Garbage Collector](https://openjdk.java.net/jeps/363)
    - [364_ZGC on macOS (Experimental)](https://openjdk.java.net/jeps/364)
    - [365_ZGC on Windows (Experimental)](https://openjdk.java.net/jeps/365)
    - [366_Deprecate the ParallelScavenge + SerialOld GC Combination](https://openjdk.java.net/jeps/366)
- JDK15
    - [377_ZGC: A Scalable Low-Latency Garbage Collector (Production)](https://openjdk.java.net/jeps/377)
    - [379_Shenandoah: A Low-Pause-Time Garbage Collector (Production)](https://openjdk.java.net/jeps/379)
- JDK16
    - [376_ZGC: Concurrent Thread-Stack Processing](https://openjdk.java.net/jeps/376)
    - [414_Vector API (Second Incubator)](https://openjdk.java.net/jeps/414)

### Tools
- JDK12
    - [230_Microbenchmark Suite](https://openjdk.java.net/jeps/230)
- JDK14
    - [343_Packaging Tool (Incubator)](https://openjdk.java.net/jeps/343)
    - [349_JFR Event Streaming](https://openjdk.java.net/jeps/349)
    - [367_Remove the Pack200 Tools and API](https://openjdk.java.net/jeps/367)
- JDK15
    - [372_Remove the Nashorn JavaScript Engine](https://openjdk.java.net/jeps/372)
- JDK16 
    - [392_Packaging Tool](https://openjdk.java.net/jeps/392)
- JDK17
    - [356_Enhanced Pseudo-Random Number Generators](https://openjdk.java.net/jeps/356)
  
### Memory
- JDK14
    - [352_Non-Volatile Mapped Byte Buffers](https://openjdk.java.net/jeps/352)
    - [370_Foreign-Memory Access API (Incubator)](https://openjdk.java.net/jeps/370)
- JDK15
    - [383_Foreign-Memory Access API (Second Incubator)](https://openjdk.java.net/jeps/383)
- JDK16
    - [393_Foreign-Memory Access API (Third Incubator)](https://openjdk.java.net/jeps/393)
- JDK17
    - [412_Foreign Function & Memory API (Incubator)](https://openjdk.java.net/jeps/412)
        
### JVM
- JDK12
    - [334_JVM Constants API](https://openjdk.java.net/jeps/334)
- JDK15
    - [374_Deprecate and Disable Biased Locking](https://openjdk.java.net/jeps/374)
    - [381_Remove the Solaris and SPARC Ports](https://openjdk.java.net/jeps/381)
- JDK16
    - [386_Alpine Linux Port](https://openjdk.java.net/jeps/386)
    - [387_Elastic Metaspace](https://openjdk.java.net/jeps/387)
    - [388_Windows/AArch64 Port](https://openjdk.java.net/jeps/388)
- JDK17
    - [391_macOS/AArch64 Port](https://openjdk.java.net/jeps/391)
    - [410_Remove the Experimental AOT and JIT Compiler](https://openjdk.java.net/jeps/410)

### ETC
- JDK12
    - [340_One AArch64 Port, Not Two](https://openjdk.java.net/jeps/340)
    - [341_Default CDS Archives](https://openjdk.java.net/jeps/341)
- JDK13
    - [350_Dynamic CDS Archives](https://openjdk.java.net/jeps/350)
    - [353_Reimplement the Legacy Socket API](https://openjdk.java.net/jeps/353)
- JDK14
    - [362_Deprecate the Solaris and SPARC Ports](https://openjdk.java.net/jeps/362)
- JDK15
    - [339_Edwards-Curve Digital Signature Algorithm (EdDSA)](https://openjdk.java.net/jeps/339)
    - [373_Reimplement the Legacy DatagramSocket API](https://openjdk.java.net/jeps/373)
    - [385_Deprecate RMI Activation for Removal](https://openjdk.java.net/jeps/385)
- JDK16
    - [347_Enable C++14 Language Features](https://openjdk.java.net/jeps/347)
    - [357_Migrate from Mercurial to Git](https://openjdk.java.net/jeps/357)
    - [369_Migrate to GitHub](https://openjdk.java.net/jeps/369)
    - [380_Unix-Domain Socket Channels](https://openjdk.java.net/jeps/380) 
    - [389_Foreign Linker API (Incubator)](https://openjdk.java.net/jeps/389)
    - [390_Warnings for Value-Based Classes](https://openjdk.java.net/jeps/390)
    - [396_Strongly Encapsulate JDK Internals by Default](https://openjdk.java.net/jeps/396)

- JDK17
    - [382_New macOS Rendering Pipeline](https://openjdk.java.net/jeps/382)
    - [398_Deprecate the Applet API for Removal](https://openjdk.java.net/jeps/398)
    - [403_Strongly Encapsulate JDK Internals](https://openjdk.java.net/jeps/403)
    - [407_Remove RMI Activation](https://openjdk.java.net/jeps/407)
    - [411_Deprecate the Security Manager for Removal](https://openjdk.java.net/jeps/411)
    - [415_Context-Specific Deserialization Filters](https://openjdk.java.net/jeps/415)
---

# Language Spec

## JDK12

### [325_Switch Expressions (Preview)](https://openjdk.java.net/jeps/325)

Switch가 Expression이 됨
```java
return switch() {
    ...
}
```

## JDK13
### [354_Switch Expressions (Second Preview)](https://openjdk.java.net/jeps/354)

요약쓰

### [355_Text Blocks (Preview)](https://openjdk.java.net/jeps/355)

요약쓰