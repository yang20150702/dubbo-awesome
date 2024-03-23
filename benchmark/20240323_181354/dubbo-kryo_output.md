# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 1.577 ops/ms
Iteration   1: 7.127 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.127 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 5.805 ops/ms
Iteration   1: 13.007 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.007 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 5.407 ops/ms
Iteration   1: 11.735 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.735 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 4.842 ops/ms
Iteration   1: 8.932 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.932 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.855 ±(99.9%) 0.085 ms/op
Iteration   1: 2.452 ±(99.9%) 0.025 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.452 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.310 ±(99.9%) 0.054 ms/op
Iteration   1: 1.742 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.742 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 3.287 ±(99.9%) 0.074 ms/op
Iteration   1: 1.891 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.891 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 4.569 ±(99.9%) 0.087 ms/op
Iteration   1: 3.259 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.259 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.488 ±(99.9%) 0.085 ms/op
Iteration   1: 2.248 ±(99.9%) 0.039 ms/op
                 createUser·p0.00:   0.687 ms/op
                 createUser·p0.50:   1.956 ms/op
                 createUser·p0.90:   2.699 ms/op
                 createUser·p0.95:   3.084 ms/op
                 createUser·p0.99:   8.995 ms/op
                 createUser·p0.999:  21.706 ms/op
                 createUser·p0.9999: 26.462 ms/op
                 createUser·p1.00:   26.477 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14285
  mean =      2.248 ±(99.9%) 0.039 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11682 
    [ 2.500,  5.000) = 2246 
    [ 5.000,  7.500) = 160 
    [ 7.500, 10.000) = 112 
    [10.000, 12.500) = 21 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.687 ms/op
     p(50.0000) =      1.956 ms/op
     p(90.0000) =      2.699 ms/op
     p(95.0000) =      3.084 ms/op
     p(99.0000) =      8.995 ms/op
     p(99.9000) =     21.706 ms/op
     p(99.9900) =     26.462 ms/op
     p(99.9990) =     26.477 ms/op
     p(99.9999) =     26.477 ms/op
    p(100.0000) =     26.477 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 3.217 ±(99.9%) 0.087 ms/op
Iteration   1: 1.865 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   0.478 ms/op
                 existUser·p0.50:   1.667 ms/op
                 existUser·p0.90:   2.462 ms/op
                 existUser·p0.95:   2.659 ms/op
                 existUser·p0.99:   4.119 ms/op
                 existUser·p0.999:  11.736 ms/op
                 existUser·p0.9999: 12.445 ms/op
                 existUser·p1.00:   12.468 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17135
  mean =      1.865 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 374 
    [ 1.250,  2.500) = 15311 
    [ 2.500,  3.750) = 1244 
    [ 3.750,  5.000) = 120 
    [ 5.000,  6.250) = 18 
    [ 6.250,  7.500) = 33 
    [ 7.500,  8.750) = 3 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 2 
    [11.250, 12.500) = 30 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.478 ms/op
     p(50.0000) =      1.667 ms/op
     p(90.0000) =      2.462 ms/op
     p(95.0000) =      2.659 ms/op
     p(99.0000) =      4.119 ms/op
     p(99.9000) =     11.736 ms/op
     p(99.9900) =     12.445 ms/op
     p(99.9990) =     12.468 ms/op
     p(99.9999) =     12.468 ms/op
    p(100.0000) =     12.468 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.084 ±(99.9%) 0.078 ms/op
Iteration   1: 2.095 ±(99.9%) 0.033 ms/op
                 getUser·p0.00:   0.579 ms/op
                 getUser·p0.50:   1.896 ms/op
                 getUser·p0.90:   2.511 ms/op
                 getUser·p0.95:   2.833 ms/op
                 getUser·p0.99:   8.538 ms/op
                 getUser·p0.999:  17.521 ms/op
                 getUser·p0.9999: 18.562 ms/op
                 getUser·p1.00:   18.579 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15286
  mean =      2.095 ±(99.9%) 0.033 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 279 
    [ 1.250,  2.500) = 13413 
    [ 2.500,  3.750) = 1166 
    [ 3.750,  5.000) = 125 
    [ 5.000,  6.250) = 47 
    [ 6.250,  7.500) = 47 
    [ 7.500,  8.750) = 73 
    [ 8.750, 10.000) = 31 
    [10.000, 11.250) = 41 
    [11.250, 12.500) = 27 
    [12.500, 13.750) = 5 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 17 
    [17.500, 18.750) = 15 

  Percentiles, ms/op:
      p(0.0000) =      0.579 ms/op
     p(50.0000) =      1.896 ms/op
     p(90.0000) =      2.511 ms/op
     p(95.0000) =      2.833 ms/op
     p(99.0000) =      8.538 ms/op
     p(99.9000) =     17.521 ms/op
     p(99.9900) =     18.562 ms/op
     p(99.9990) =     18.579 ms/op
     p(99.9999) =     18.579 ms/op
    p(100.0000) =     18.579 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.649 ±(99.9%) 0.151 ms/op
Iteration   1: 3.048 ±(99.9%) 0.056 ms/op
                 listUser·p0.00:   0.907 ms/op
                 listUser·p0.50:   2.699 ms/op
                 listUser·p0.90:   3.981 ms/op
                 listUser·p0.95:   4.425 ms/op
                 listUser·p0.99:   7.038 ms/op
                 listUser·p0.999:  30.425 ms/op
                 listUser·p0.9999: 31.782 ms/op
                 listUser·p1.00:   31.818 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10495
  mean =      3.048 ±(99.9%) 0.056 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3427 
    [ 2.500,  5.000) = 6778 
    [ 5.000,  7.500) = 219 
    [ 7.500, 10.000) = 39 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 13 
    [30.000, 32.500) = 19 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.907 ms/op
     p(50.0000) =      2.699 ms/op
     p(90.0000) =      3.981 ms/op
     p(95.0000) =      4.425 ms/op
     p(99.0000) =      7.038 ms/op
     p(99.9000) =     30.425 ms/op
     p(99.9900) =     31.782 ms/op
     p(99.9990) =     31.818 ms/op
     p(99.9999) =     31.818 ms/op
    p(100.0000) =     31.818 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.127          ops/ms
ClientSimple.existUser                       thrpt         13.007          ops/ms
ClientSimple.getUser                         thrpt         11.735          ops/ms
ClientSimple.listUser                        thrpt          8.932          ops/ms
ClientSimple.createUser                       avgt          2.452           ms/op
ClientSimple.existUser                        avgt          1.742           ms/op
ClientSimple.getUser                          avgt          1.891           ms/op
ClientSimple.listUser                         avgt          3.259           ms/op
ClientSimple.createUser                     sample  14285   2.248 ± 0.039   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.687           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.956           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.699           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.084           ms/op
ClientSimple.createUser:createUser·p0.99    sample          8.995           ms/op
ClientSimple.createUser:createUser·p0.999   sample         21.706           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         26.462           ms/op
ClientSimple.createUser:createUser·p1.00    sample         26.477           ms/op
ClientSimple.existUser                      sample  17135   1.865 ± 0.017   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.478           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.667           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.462           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.659           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.119           ms/op
ClientSimple.existUser:existUser·p0.999     sample         11.736           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         12.445           ms/op
ClientSimple.existUser:existUser·p1.00      sample         12.468           ms/op
ClientSimple.getUser                        sample  15286   2.095 ± 0.033   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.579           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.896           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.511           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.833           ms/op
ClientSimple.getUser:getUser·p0.99          sample          8.538           ms/op
ClientSimple.getUser:getUser·p0.999         sample         17.521           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         18.562           ms/op
ClientSimple.getUser:getUser·p1.00          sample         18.579           ms/op
ClientSimple.listUser                       sample  10495   3.048 ± 0.056   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.907           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.699           ms/op
ClientSimple.listUser:listUser·p0.90        sample          3.981           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.425           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.038           ms/op
ClientSimple.listUser:listUser·p0.999       sample         30.425           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         31.782           ms/op
ClientSimple.listUser:listUser·p1.00        sample         31.818           ms/op

Benchmark result is saved to 1711217374539.json
