# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 1.855 ops/ms
Iteration   1: 7.279 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.279 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 5.879 ops/ms
Iteration   1: 12.106 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.106 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 5.338 ops/ms
Iteration   1: 13.254 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.254 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 5.056 ops/ms
Iteration   1: 8.807 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.807 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 4.576 ±(99.9%) 0.085 ms/op
Iteration   1: 2.342 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.342 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.331 ±(99.9%) 0.065 ms/op
Iteration   1: 1.618 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.618 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 3.225 ±(99.9%) 0.084 ms/op
Iteration   1: 2.175 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.175 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 5.919 ±(99.9%) 0.134 ms/op
Iteration   1: 3.693 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.693 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.432 ±(99.9%) 0.097 ms/op
Iteration   1: 2.592 ±(99.9%) 0.041 ms/op
                 createUser·p0.00:   0.697 ms/op
                 createUser·p0.50:   2.454 ms/op
                 createUser·p0.90:   3.154 ms/op
                 createUser·p0.95:   3.514 ms/op
                 createUser·p0.99:   11.741 ms/op
                 createUser·p0.999:  16.089 ms/op
                 createUser·p0.9999: 22.111 ms/op
                 createUser·p1.00:   22.118 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 12336
  mean =      2.592 ±(99.9%) 0.041 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6589 
    [ 2.500,  5.000) = 5481 
    [ 5.000,  7.500) = 103 
    [ 7.500, 10.000) = 3 
    [10.000, 12.500) = 99 
    [12.500, 15.000) = 29 
    [15.000, 17.500) = 25 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.697 ms/op
     p(50.0000) =      2.454 ms/op
     p(90.0000) =      3.154 ms/op
     p(95.0000) =      3.514 ms/op
     p(99.0000) =     11.741 ms/op
     p(99.9000) =     16.089 ms/op
     p(99.9900) =     22.111 ms/op
     p(99.9990) =     22.118 ms/op
     p(99.9999) =     22.118 ms/op
    p(100.0000) =     22.118 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 2.939 ±(99.9%) 0.066 ms/op
Iteration   1: 1.860 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   0.599 ms/op
                 existUser·p0.50:   1.765 ms/op
                 existUser·p0.90:   2.200 ms/op
                 existUser·p0.95:   2.351 ms/op
                 existUser·p0.99:   3.277 ms/op
                 existUser·p0.999:  12.255 ms/op
                 existUser·p0.9999: 12.510 ms/op
                 existUser·p1.00:   12.534 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17192
  mean =      1.860 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 201 
    [ 1.250,  2.500) = 16476 
    [ 2.500,  3.750) = 380 
    [ 3.750,  5.000) = 18 
    [ 5.000,  6.250) = 65 
    [ 6.250,  7.500) = 16 
    [ 7.500,  8.750) = 4 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 30 
    [12.500, 13.750) = 2 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.599 ms/op
     p(50.0000) =      1.765 ms/op
     p(90.0000) =      2.200 ms/op
     p(95.0000) =      2.351 ms/op
     p(99.0000) =      3.277 ms/op
     p(99.9000) =     12.255 ms/op
     p(99.9900) =     12.510 ms/op
     p(99.9990) =     12.534 ms/op
     p(99.9999) =     12.534 ms/op
    p(100.0000) =     12.534 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.365 ±(99.9%) 0.101 ms/op
Iteration   1: 2.146 ±(99.9%) 0.029 ms/op
                 getUser·p0.00:   0.686 ms/op
                 getUser·p0.50:   2.011 ms/op
                 getUser·p0.90:   2.593 ms/op
                 getUser·p0.95:   2.859 ms/op
                 getUser·p0.99:   4.625 ms/op
                 getUser·p0.999:  13.828 ms/op
                 getUser·p0.9999: 16.745 ms/op
                 getUser·p1.00:   16.876 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14972
  mean =      2.146 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 136 
    [ 1.250,  2.500) = 12895 
    [ 2.500,  3.750) = 1679 
    [ 3.750,  5.000) = 124 
    [ 5.000,  6.250) = 10 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 4 
    [10.000, 11.250) = 25 
    [11.250, 12.500) = 20 
    [12.500, 13.750) = 56 
    [13.750, 15.000) = 20 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 3 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.686 ms/op
     p(50.0000) =      2.011 ms/op
     p(90.0000) =      2.593 ms/op
     p(95.0000) =      2.859 ms/op
     p(99.0000) =      4.625 ms/op
     p(99.9000) =     13.828 ms/op
     p(99.9900) =     16.745 ms/op
     p(99.9990) =     16.876 ms/op
     p(99.9999) =     16.876 ms/op
    p(100.0000) =     16.876 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 5.925 ±(99.9%) 0.160 ms/op
Iteration   1: 3.842 ±(99.9%) 0.062 ms/op
                 listUser·p0.00:   1.118 ms/op
                 listUser·p0.50:   3.736 ms/op
                 listUser·p0.90:   4.538 ms/op
                 listUser·p0.95:   4.899 ms/op
                 listUser·p0.99:   9.273 ms/op
                 listUser·p0.999:  25.657 ms/op
                 listUser·p0.9999: 28.967 ms/op
                 listUser·p1.00:   28.967 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8335
  mean =      3.842 ±(99.9%) 0.062 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 579 
    [ 2.500,  5.000) = 7384 
    [ 5.000,  7.500) = 215 
    [ 7.500, 10.000) = 87 
    [10.000, 12.500) = 28 
    [12.500, 15.000) = 9 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 26 

  Percentiles, ms/op:
      p(0.0000) =      1.118 ms/op
     p(50.0000) =      3.736 ms/op
     p(90.0000) =      4.538 ms/op
     p(95.0000) =      4.899 ms/op
     p(99.0000) =      9.273 ms/op
     p(99.9000) =     25.657 ms/op
     p(99.9900) =     28.967 ms/op
     p(99.9990) =     28.967 ms/op
     p(99.9999) =     28.967 ms/op
    p(100.0000) =     28.967 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.279          ops/ms
ClientSimple.existUser                       thrpt         12.106          ops/ms
ClientSimple.getUser                         thrpt         13.254          ops/ms
ClientSimple.listUser                        thrpt          8.807          ops/ms
ClientSimple.createUser                       avgt          2.342           ms/op
ClientSimple.existUser                        avgt          1.618           ms/op
ClientSimple.getUser                          avgt          2.175           ms/op
ClientSimple.listUser                         avgt          3.693           ms/op
ClientSimple.createUser                     sample  12336   2.592 ± 0.041   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.697           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.454           ms/op
ClientSimple.createUser:createUser·p0.90    sample          3.154           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.514           ms/op
ClientSimple.createUser:createUser·p0.99    sample         11.741           ms/op
ClientSimple.createUser:createUser·p0.999   sample         16.089           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         22.111           ms/op
ClientSimple.createUser:createUser·p1.00    sample         22.118           ms/op
ClientSimple.existUser                      sample  17192   1.860 ± 0.015   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.599           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.765           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.200           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.351           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.277           ms/op
ClientSimple.existUser:existUser·p0.999     sample         12.255           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         12.510           ms/op
ClientSimple.existUser:existUser·p1.00      sample         12.534           ms/op
ClientSimple.getUser                        sample  14972   2.146 ± 0.029   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.686           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.011           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.593           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.859           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.625           ms/op
ClientSimple.getUser:getUser·p0.999         sample         13.828           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         16.745           ms/op
ClientSimple.getUser:getUser·p1.00          sample         16.876           ms/op
ClientSimple.listUser                       sample   8335   3.842 ± 0.062   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.118           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.736           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.538           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.899           ms/op
ClientSimple.listUser:listUser·p0.99        sample          9.273           ms/op
ClientSimple.listUser:listUser·p0.999       sample         25.657           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         28.967           ms/op
ClientSimple.listUser:listUser·p1.00        sample         28.967           ms/op

Benchmark result is saved to 1718930423174.json
