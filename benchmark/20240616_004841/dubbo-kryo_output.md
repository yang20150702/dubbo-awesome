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
# Warmup Iteration   1: 1.918 ops/ms
Iteration   1: 6.961 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.961 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.214 ops/ms
Iteration   1: 12.394 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.394 ops/ms


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
# Warmup Iteration   1: 6.129 ops/ms
Iteration   1: 14.104 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  14.104 ops/ms


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
# Warmup Iteration   1: 5.518 ops/ms
Iteration   1: 8.951 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.951 ops/ms


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
# Warmup Iteration   1: 3.777 ±(99.9%) 0.064 ms/op
Iteration   1: 2.163 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.163 ms/op


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
# Warmup Iteration   1: 3.098 ±(99.9%) 0.053 ms/op
Iteration   1: 1.724 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.724 ms/op


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
# Warmup Iteration   1: 3.505 ±(99.9%) 0.063 ms/op
Iteration   1: 1.932 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.932 ms/op


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
# Warmup Iteration   1: 6.011 ±(99.9%) 0.140 ms/op
Iteration   1: 3.877 ±(99.9%) 0.027 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.877 ms/op


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
# Warmup Iteration   1: 3.425 ±(99.9%) 0.096 ms/op
Iteration   1: 2.663 ±(99.9%) 0.163 ms/op
                 createUser·p0.00:   0.387 ms/op
                 createUser·p0.50:   2.085 ms/op
                 createUser·p0.90:   2.826 ms/op
                 createUser·p0.95:   3.224 ms/op
                 createUser·p0.99:   14.156 ms/op
                 createUser·p0.999:  82.445 ms/op
                 createUser·p0.9999: 100.089 ms/op
                 createUser·p1.00:   101.843 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 11996
  mean =      2.663 ±(99.9%) 0.163 ms/op

  Histogram, ms/op:
    [  0.000,  12.500) = 11858 
    [ 12.500,  25.000) = 49 
    [ 25.000,  37.500) = 16 
    [ 37.500,  50.000) = 12 
    [ 50.000,  62.500) = 16 
    [ 62.500,  75.000) = 17 
    [ 75.000,  87.500) = 22 
    [ 87.500, 100.000) = 5 
    [100.000, 112.500) = 1 
    [112.500, 125.000) = 0 
    [125.000, 137.500) = 0 
    [137.500, 150.000) = 0 
    [150.000, 162.500) = 0 
    [162.500, 175.000) = 0 
    [175.000, 187.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.387 ms/op
     p(50.0000) =      2.085 ms/op
     p(90.0000) =      2.826 ms/op
     p(95.0000) =      3.224 ms/op
     p(99.0000) =     14.156 ms/op
     p(99.9000) =     82.445 ms/op
     p(99.9900) =    100.089 ms/op
     p(99.9990) =    101.843 ms/op
     p(99.9999) =    101.843 ms/op
    p(100.0000) =    101.843 ms/op


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
# Warmup Iteration   1: 2.852 ±(99.9%) 0.072 ms/op
Iteration   1: 1.709 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   0.723 ms/op
                 existUser·p0.50:   1.599 ms/op
                 existUser·p0.90:   2.052 ms/op
                 existUser·p0.95:   2.255 ms/op
                 existUser·p0.99:   3.365 ms/op
                 existUser·p0.999:  15.155 ms/op
                 existUser·p0.9999: 15.370 ms/op
                 existUser·p1.00:   15.385 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 18749
  mean =      1.709 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 271 
    [ 1.250,  2.500) = 18034 
    [ 2.500,  3.750) = 303 
    [ 3.750,  5.000) = 45 
    [ 5.000,  6.250) = 63 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 9 
    [15.000, 16.250) = 23 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.723 ms/op
     p(50.0000) =      1.599 ms/op
     p(90.0000) =      2.052 ms/op
     p(95.0000) =      2.255 ms/op
     p(99.0000) =      3.365 ms/op
     p(99.9000) =     15.155 ms/op
     p(99.9900) =     15.370 ms/op
     p(99.9990) =     15.385 ms/op
     p(99.9999) =     15.385 ms/op
    p(100.0000) =     15.385 ms/op


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
# Warmup Iteration   1: 3.516 ±(99.9%) 0.096 ms/op
Iteration   1: 1.919 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   0.796 ms/op
                 getUser·p0.50:   1.823 ms/op
                 getUser·p0.90:   2.290 ms/op
                 getUser·p0.95:   2.527 ms/op
                 getUser·p0.99:   4.068 ms/op
                 getUser·p0.999:  12.206 ms/op
                 getUser·p0.9999: 12.462 ms/op
                 getUser·p1.00:   12.517 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16758
  mean =      1.919 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 232 
    [ 1.250,  2.500) = 15622 
    [ 2.500,  3.750) = 703 
    [ 3.750,  5.000) = 77 
    [ 5.000,  6.250) = 64 
    [ 6.250,  7.500) = 16 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 11 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 31 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.796 ms/op
     p(50.0000) =      1.823 ms/op
     p(90.0000) =      2.290 ms/op
     p(95.0000) =      2.527 ms/op
     p(99.0000) =      4.068 ms/op
     p(99.9000) =     12.206 ms/op
     p(99.9900) =     12.462 ms/op
     p(99.9990) =     12.517 ms/op
     p(99.9999) =     12.517 ms/op
    p(100.0000) =     12.517 ms/op


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
# Warmup Iteration   1: 4.302 ±(99.9%) 0.124 ms/op
Iteration   1: 3.467 ±(99.9%) 0.048 ms/op
                 listUser·p0.00:   1.061 ms/op
                 listUser·p0.50:   3.346 ms/op
                 listUser·p0.90:   4.157 ms/op
                 listUser·p0.95:   4.522 ms/op
                 listUser·p0.99:   7.478 ms/op
                 listUser·p0.999:  23.579 ms/op
                 listUser·p0.9999: 24.052 ms/op
                 listUser·p1.00:   24.052 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9213
  mean =      3.467 ±(99.9%) 0.048 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 674 
    [ 2.500,  5.000) = 8277 
    [ 5.000,  7.500) = 171 
    [ 7.500, 10.000) = 59 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 26 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.061 ms/op
     p(50.0000) =      3.346 ms/op
     p(90.0000) =      4.157 ms/op
     p(95.0000) =      4.522 ms/op
     p(99.0000) =      7.478 ms/op
     p(99.9000) =     23.579 ms/op
     p(99.9900) =     24.052 ms/op
     p(99.9990) =     24.052 ms/op
     p(99.9999) =     24.052 ms/op
    p(100.0000) =     24.052 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt    Score   Error   Units
ClientSimple.createUser                      thrpt           6.961          ops/ms
ClientSimple.existUser                       thrpt          12.394          ops/ms
ClientSimple.getUser                         thrpt          14.104          ops/ms
ClientSimple.listUser                        thrpt           8.951          ops/ms
ClientSimple.createUser                       avgt           2.163           ms/op
ClientSimple.existUser                        avgt           1.724           ms/op
ClientSimple.getUser                          avgt           1.932           ms/op
ClientSimple.listUser                         avgt           3.877           ms/op
ClientSimple.createUser                     sample  11996    2.663 ± 0.163   ms/op
ClientSimple.createUser:createUser·p0.00    sample           0.387           ms/op
ClientSimple.createUser:createUser·p0.50    sample           2.085           ms/op
ClientSimple.createUser:createUser·p0.90    sample           2.826           ms/op
ClientSimple.createUser:createUser·p0.95    sample           3.224           ms/op
ClientSimple.createUser:createUser·p0.99    sample          14.156           ms/op
ClientSimple.createUser:createUser·p0.999   sample          82.445           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         100.089           ms/op
ClientSimple.createUser:createUser·p1.00    sample         101.843           ms/op
ClientSimple.existUser                      sample  18749    1.709 ± 0.016   ms/op
ClientSimple.existUser:existUser·p0.00      sample           0.723           ms/op
ClientSimple.existUser:existUser·p0.50      sample           1.599           ms/op
ClientSimple.existUser:existUser·p0.90      sample           2.052           ms/op
ClientSimple.existUser:existUser·p0.95      sample           2.255           ms/op
ClientSimple.existUser:existUser·p0.99      sample           3.365           ms/op
ClientSimple.existUser:existUser·p0.999     sample          15.155           ms/op
ClientSimple.existUser:existUser·p0.9999    sample          15.370           ms/op
ClientSimple.existUser:existUser·p1.00      sample          15.385           ms/op
ClientSimple.getUser                        sample  16758    1.919 ± 0.017   ms/op
ClientSimple.getUser:getUser·p0.00          sample           0.796           ms/op
ClientSimple.getUser:getUser·p0.50          sample           1.823           ms/op
ClientSimple.getUser:getUser·p0.90          sample           2.290           ms/op
ClientSimple.getUser:getUser·p0.95          sample           2.527           ms/op
ClientSimple.getUser:getUser·p0.99          sample           4.068           ms/op
ClientSimple.getUser:getUser·p0.999         sample          12.206           ms/op
ClientSimple.getUser:getUser·p0.9999        sample          12.462           ms/op
ClientSimple.getUser:getUser·p1.00          sample          12.517           ms/op
ClientSimple.listUser                       sample   9213    3.467 ± 0.048   ms/op
ClientSimple.listUser:listUser·p0.00        sample           1.061           ms/op
ClientSimple.listUser:listUser·p0.50        sample           3.346           ms/op
ClientSimple.listUser:listUser·p0.90        sample           4.157           ms/op
ClientSimple.listUser:listUser·p0.95        sample           4.522           ms/op
ClientSimple.listUser:listUser·p0.99        sample           7.478           ms/op
ClientSimple.listUser:listUser·p0.999       sample          23.579           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          24.052           ms/op
ClientSimple.listUser:listUser·p1.00        sample          24.052           ms/op

Benchmark result is saved to 1718498666170.json
