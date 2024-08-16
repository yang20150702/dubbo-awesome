# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 1.785 ops/ms
Iteration   1: 7.394 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.394 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 4.985 ops/ms
Iteration   1: 11.042 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.042 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 16.67% complete, ETA 00:01:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.035 ops/ms
Iteration   1: 9.392 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  9.392 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 4.398 ops/ms
Iteration   1: 8.282 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.282 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 4.323 ±(99.9%) 0.085 ms/op
Iteration   1: 2.093 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.093 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.223 ±(99.9%) 0.053 ms/op
Iteration   1: 1.920 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.920 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 3.176 ±(99.9%) 0.062 ms/op
Iteration   1: 1.951 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.951 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 5.090 ±(99.9%) 0.121 ms/op
Iteration   1: 3.692 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.692 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.707 ±(99.9%) 0.090 ms/op
Iteration   1: 2.646 ±(99.9%) 0.039 ms/op
                 createUser·p0.00:   1.044 ms/op
                 createUser·p0.50:   2.314 ms/op
                 createUser·p0.90:   3.740 ms/op
                 createUser·p0.95:   4.094 ms/op
                 createUser·p0.99:   8.569 ms/op
                 createUser·p0.999:  15.925 ms/op
                 createUser·p0.9999: 16.155 ms/op
                 createUser·p1.00:   16.155 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 12471
  mean =      2.646 ±(99.9%) 0.039 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 47 
    [ 1.250,  2.500) = 7669 
    [ 2.500,  3.750) = 3538 
    [ 3.750,  5.000) = 996 
    [ 5.000,  6.250) = 86 
    [ 6.250,  7.500) = 8 
    [ 7.500,  8.750) = 9 
    [ 8.750, 10.000) = 27 
    [10.000, 11.250) = 11 
    [11.250, 12.500) = 16 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 32 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.044 ms/op
     p(50.0000) =      2.314 ms/op
     p(90.0000) =      3.740 ms/op
     p(95.0000) =      4.094 ms/op
     p(99.0000) =      8.569 ms/op
     p(99.9000) =     15.925 ms/op
     p(99.9900) =     16.155 ms/op
     p(99.9990) =     16.155 ms/op
     p(99.9999) =     16.155 ms/op
    p(100.0000) =     16.155 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 2.898 ±(99.9%) 0.064 ms/op
Iteration   1: 1.702 ±(99.9%) 0.035 ms/op
                 existUser·p0.00:   0.462 ms/op
                 existUser·p0.50:   1.524 ms/op
                 existUser·p0.90:   1.989 ms/op
                 existUser·p0.95:   2.269 ms/op
                 existUser·p0.99:   3.585 ms/op
                 existUser·p0.999:  31.156 ms/op
                 existUser·p0.9999: 31.368 ms/op
                 existUser·p1.00:   31.425 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 18595
  mean =      1.702 ±(99.9%) 0.035 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18051 
    [ 2.500,  5.000) = 391 
    [ 5.000,  7.500) = 24 
    [ 7.500, 10.000) = 8 
    [10.000, 12.500) = 88 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 32 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.462 ms/op
     p(50.0000) =      1.524 ms/op
     p(90.0000) =      1.989 ms/op
     p(95.0000) =      2.269 ms/op
     p(99.0000) =      3.585 ms/op
     p(99.9000) =     31.156 ms/op
     p(99.9900) =     31.368 ms/op
     p(99.9990) =     31.425 ms/op
     p(99.9999) =     31.425 ms/op
    p(100.0000) =     31.425 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.387 ±(99.9%) 0.087 ms/op
Iteration   1: 1.894 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   0.778 ms/op
                 getUser·p0.50:   1.784 ms/op
                 getUser·p0.90:   2.298 ms/op
                 getUser·p0.95:   2.511 ms/op
                 getUser·p0.99:   3.257 ms/op
                 getUser·p0.999:  13.533 ms/op
                 getUser·p0.9999: 13.758 ms/op
                 getUser·p1.00:   13.894 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16893
  mean =      1.894 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 71 
    [ 1.250,  2.500) = 15953 
    [ 2.500,  3.750) = 725 
    [ 3.750,  5.000) = 52 
    [ 5.000,  6.250) = 57 
    [ 6.250,  7.500) = 2 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 31 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.778 ms/op
     p(50.0000) =      1.784 ms/op
     p(90.0000) =      2.298 ms/op
     p(95.0000) =      2.511 ms/op
     p(99.0000) =      3.257 ms/op
     p(99.9000) =     13.533 ms/op
     p(99.9900) =     13.758 ms/op
     p(99.9990) =     13.894 ms/op
     p(99.9999) =     13.894 ms/op
    p(100.0000) =     13.894 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.497 ±(99.9%) 0.145 ms/op
Iteration   1: 3.520 ±(99.9%) 0.033 ms/op
                 listUser·p0.00:   0.867 ms/op
                 listUser·p0.50:   3.506 ms/op
                 listUser·p0.90:   4.227 ms/op
                 listUser·p0.95:   4.448 ms/op
                 listUser·p0.99:   6.177 ms/op
                 listUser·p0.999:  14.352 ms/op
                 listUser·p0.9999: 15.630 ms/op
                 listUser·p1.00:   15.630 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9125
  mean =      3.520 ±(99.9%) 0.033 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 5 
    [ 1.250,  2.500) = 605 
    [ 2.500,  3.750) = 5588 
    [ 3.750,  5.000) = 2704 
    [ 5.000,  6.250) = 139 
    [ 6.250,  7.500) = 23 
    [ 7.500,  8.750) = 30 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 28 
    [15.000, 16.250) = 3 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.867 ms/op
     p(50.0000) =      3.506 ms/op
     p(90.0000) =      4.227 ms/op
     p(95.0000) =      4.448 ms/op
     p(99.0000) =      6.177 ms/op
     p(99.9000) =     14.352 ms/op
     p(99.9900) =     15.630 ms/op
     p(99.9990) =     15.630 ms/op
     p(99.9999) =     15.630 ms/op
    p(100.0000) =     15.630 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.394          ops/ms
ClientSimple.existUser                       thrpt         11.042          ops/ms
ClientSimple.getUser                         thrpt          9.392          ops/ms
ClientSimple.listUser                        thrpt          8.282          ops/ms
ClientSimple.createUser                       avgt          2.093           ms/op
ClientSimple.existUser                        avgt          1.920           ms/op
ClientSimple.getUser                          avgt          1.951           ms/op
ClientSimple.listUser                         avgt          3.692           ms/op
ClientSimple.createUser                     sample  12471   2.646 ± 0.039   ms/op
ClientSimple.createUser:createUser·p0.00    sample          1.044           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.314           ms/op
ClientSimple.createUser:createUser·p0.90    sample          3.740           ms/op
ClientSimple.createUser:createUser·p0.95    sample          4.094           ms/op
ClientSimple.createUser:createUser·p0.99    sample          8.569           ms/op
ClientSimple.createUser:createUser·p0.999   sample         15.925           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         16.155           ms/op
ClientSimple.createUser:createUser·p1.00    sample         16.155           ms/op
ClientSimple.existUser                      sample  18595   1.702 ± 0.035   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.462           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.524           ms/op
ClientSimple.existUser:existUser·p0.90      sample          1.989           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.269           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.585           ms/op
ClientSimple.existUser:existUser·p0.999     sample         31.156           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         31.368           ms/op
ClientSimple.existUser:existUser·p1.00      sample         31.425           ms/op
ClientSimple.getUser                        sample  16893   1.894 ± 0.016   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.778           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.784           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.298           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.511           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.257           ms/op
ClientSimple.getUser:getUser·p0.999         sample         13.533           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         13.758           ms/op
ClientSimple.getUser:getUser·p1.00          sample         13.894           ms/op
ClientSimple.listUser                       sample   9125   3.520 ± 0.033   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.867           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.506           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.227           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.448           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.177           ms/op
ClientSimple.listUser:listUser·p0.999       sample         14.352           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         15.630           ms/op
ClientSimple.listUser:listUser·p1.00        sample         15.630           ms/op

Benchmark result is saved to 1723810701448.json
