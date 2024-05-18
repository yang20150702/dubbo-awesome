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
# Warmup Iteration   1: 2.102 ops/ms
Iteration   1: 7.689 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.689 ops/ms


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
# Warmup Iteration   1: 6.263 ops/ms
Iteration   1: 11.847 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.847 ops/ms


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
# Warmup Iteration   1: 5.625 ops/ms
Iteration   1: 12.510 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.510 ops/ms


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
# Warmup Iteration   1: 5.230 ops/ms
Iteration   1: 8.865 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.865 ops/ms


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
# Warmup Iteration   1: 3.525 ±(99.9%) 0.056 ms/op
Iteration   1: 1.976 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  1.976 ms/op


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
# Warmup Iteration   1: 3.084 ±(99.9%) 0.054 ms/op
Iteration   1: 1.931 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.931 ms/op


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
# Warmup Iteration   1: 3.051 ±(99.9%) 0.061 ms/op
Iteration   1: 1.818 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.818 ms/op


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
# Warmup Iteration   1: 4.465 ±(99.9%) 0.078 ms/op
Iteration   1: 3.514 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.514 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 3.530 ±(99.9%) 0.099 ms/op
Iteration   1: 2.083 ±(99.9%) 0.031 ms/op
                 createUser·p0.00:   0.478 ms/op
                 createUser·p0.50:   1.956 ms/op
                 createUser·p0.90:   2.372 ms/op
                 createUser·p0.95:   2.568 ms/op
                 createUser·p0.99:   3.713 ms/op
                 createUser·p0.999:  24.335 ms/op
                 createUser·p0.9999: 26.419 ms/op
                 createUser·p1.00:   26.804 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15340
  mean =      2.083 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14364 
    [ 2.500,  5.000) = 885 
    [ 5.000,  7.500) = 27 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.478 ms/op
     p(50.0000) =      1.956 ms/op
     p(90.0000) =      2.372 ms/op
     p(95.0000) =      2.568 ms/op
     p(99.0000) =      3.713 ms/op
     p(99.9000) =     24.335 ms/op
     p(99.9900) =     26.419 ms/op
     p(99.9990) =     26.804 ms/op
     p(99.9999) =     26.804 ms/op
    p(100.0000) =     26.804 ms/op


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
# Warmup Iteration   1: 3.015 ±(99.9%) 0.076 ms/op
Iteration   1: 2.004 ±(99.9%) 0.023 ms/op
                 existUser·p0.00:   0.333 ms/op
                 existUser·p0.50:   1.911 ms/op
                 existUser·p0.90:   2.589 ms/op
                 existUser·p0.95:   2.716 ms/op
                 existUser·p0.99:   3.278 ms/op
                 existUser·p0.999:  18.513 ms/op
                 existUser·p0.9999: 19.466 ms/op
                 existUser·p1.00:   20.120 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16039
  mean =      2.004 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13563 
    [ 2.500,  5.000) = 2409 
    [ 5.000,  7.500) = 35 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.333 ms/op
     p(50.0000) =      1.911 ms/op
     p(90.0000) =      2.589 ms/op
     p(95.0000) =      2.716 ms/op
     p(99.0000) =      3.278 ms/op
     p(99.9000) =     18.513 ms/op
     p(99.9900) =     19.466 ms/op
     p(99.9990) =     20.120 ms/op
     p(99.9999) =     20.120 ms/op
    p(100.0000) =     20.120 ms/op


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
# Warmup Iteration   1: 3.195 ±(99.9%) 0.087 ms/op
Iteration   1: 2.017 ±(99.9%) 0.032 ms/op
                 getUser·p0.00:   0.814 ms/op
                 getUser·p0.50:   1.958 ms/op
                 getUser·p0.90:   2.355 ms/op
                 getUser·p0.95:   2.507 ms/op
                 getUser·p0.99:   3.004 ms/op
                 getUser·p0.999:  28.653 ms/op
                 getUser·p0.9999: 29.873 ms/op
                 getUser·p1.00:   29.950 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15857
  mean =      2.017 ±(99.9%) 0.032 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15041 
    [ 2.500,  5.000) = 775 
    [ 5.000,  7.500) = 9 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 15 

  Percentiles, ms/op:
      p(0.0000) =      0.814 ms/op
     p(50.0000) =      1.958 ms/op
     p(90.0000) =      2.355 ms/op
     p(95.0000) =      2.507 ms/op
     p(99.0000) =      3.004 ms/op
     p(99.9000) =     28.653 ms/op
     p(99.9900) =     29.873 ms/op
     p(99.9990) =     29.950 ms/op
     p(99.9999) =     29.950 ms/op
    p(100.0000) =     29.950 ms/op


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
# Warmup Iteration   1: 4.180 ±(99.9%) 0.119 ms/op
Iteration   1: 3.232 ±(99.9%) 0.043 ms/op
                 listUser·p0.00:   1.043 ms/op
                 listUser·p0.50:   3.138 ms/op
                 listUser·p0.90:   3.924 ms/op
                 listUser·p0.95:   4.309 ms/op
                 listUser·p0.99:   7.324 ms/op
                 listUser·p0.999:  19.172 ms/op
                 listUser·p0.9999: 19.431 ms/op
                 listUser·p1.00:   19.431 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9915
  mean =      3.232 ±(99.9%) 0.043 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 7 
    [ 1.250,  2.500) = 1751 
    [ 2.500,  3.750) = 6516 
    [ 3.750,  5.000) = 1287 
    [ 5.000,  6.250) = 218 
    [ 6.250,  7.500) = 71 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 30 
    [12.500, 13.750) = 2 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.043 ms/op
     p(50.0000) =      3.138 ms/op
     p(90.0000) =      3.924 ms/op
     p(95.0000) =      4.309 ms/op
     p(99.0000) =      7.324 ms/op
     p(99.9000) =     19.172 ms/op
     p(99.9900) =     19.431 ms/op
     p(99.9990) =     19.431 ms/op
     p(99.9999) =     19.431 ms/op
    p(100.0000) =     19.431 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.689          ops/ms
ClientSimple.existUser                       thrpt         11.847          ops/ms
ClientSimple.getUser                         thrpt         12.510          ops/ms
ClientSimple.listUser                        thrpt          8.865          ops/ms
ClientSimple.createUser                       avgt          1.976           ms/op
ClientSimple.existUser                        avgt          1.931           ms/op
ClientSimple.getUser                          avgt          1.818           ms/op
ClientSimple.listUser                         avgt          3.514           ms/op
ClientSimple.createUser                     sample  15340   2.083 ± 0.031   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.478           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.956           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.372           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.568           ms/op
ClientSimple.createUser:createUser·p0.99    sample          3.713           ms/op
ClientSimple.createUser:createUser·p0.999   sample         24.335           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         26.419           ms/op
ClientSimple.createUser:createUser·p1.00    sample         26.804           ms/op
ClientSimple.existUser                      sample  16039   2.004 ± 0.023   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.333           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.911           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.589           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.716           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.278           ms/op
ClientSimple.existUser:existUser·p0.999     sample         18.513           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         19.466           ms/op
ClientSimple.existUser:existUser·p1.00      sample         20.120           ms/op
ClientSimple.getUser                        sample  15857   2.017 ± 0.032   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.814           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.958           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.355           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.507           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.004           ms/op
ClientSimple.getUser:getUser·p0.999         sample         28.653           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         29.873           ms/op
ClientSimple.getUser:getUser·p1.00          sample         29.950           ms/op
ClientSimple.listUser                       sample   9915   3.232 ± 0.043   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.043           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.138           ms/op
ClientSimple.listUser:listUser·p0.90        sample          3.924           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.309           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.324           ms/op
ClientSimple.listUser:listUser·p0.999       sample         19.172           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         19.431           ms/op
ClientSimple.listUser:listUser·p1.00        sample         19.431           ms/op

Benchmark result is saved to 1715992738291.json
