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
# Warmup Iteration   1: 1.472 ops/ms
Iteration   1: 6.336 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.336 ops/ms


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
# Warmup Iteration   1: 6.912 ops/ms
Iteration   1: 14.190 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  14.190 ops/ms


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
# Warmup Iteration   1: 6.693 ops/ms
Iteration   1: 13.175 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.175 ops/ms


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
# Warmup Iteration   1: 5.454 ops/ms
Iteration   1: 9.617 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.617 ops/ms


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
# Warmup Iteration   1: 3.961 ±(99.9%) 0.071 ms/op
Iteration   1: 2.118 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.118 ms/op


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
# Warmup Iteration   1: 3.274 ±(99.9%) 0.065 ms/op
Iteration   1: 1.770 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.770 ms/op


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
# Warmup Iteration   1: 3.454 ±(99.9%) 0.073 ms/op
Iteration   1: 2.046 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.046 ms/op


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
# Warmup Iteration   1: 4.310 ±(99.9%) 0.106 ms/op
Iteration   1: 3.395 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.395 ms/op


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
# Warmup Iteration   1: 3.243 ±(99.9%) 0.087 ms/op
Iteration   1: 2.100 ±(99.9%) 0.045 ms/op
                 createUser·p0.00:   0.477 ms/op
                 createUser·p0.50:   1.917 ms/op
                 createUser·p0.90:   2.503 ms/op
                 createUser·p0.95:   2.724 ms/op
                 createUser·p0.99:   6.152 ms/op
                 createUser·p0.999:  33.303 ms/op
                 createUser·p0.9999: 36.962 ms/op
                 createUser·p1.00:   36.962 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15220
  mean =      2.100 ±(99.9%) 0.045 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13684 
    [ 2.500,  5.000) = 1313 
    [ 5.000,  7.500) = 99 
    [ 7.500, 10.000) = 28 
    [10.000, 12.500) = 62 
    [12.500, 15.000) = 2 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 5 
    [32.500, 35.000) = 17 
    [35.000, 37.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      0.477 ms/op
     p(50.0000) =      1.917 ms/op
     p(90.0000) =      2.503 ms/op
     p(95.0000) =      2.724 ms/op
     p(99.0000) =      6.152 ms/op
     p(99.9000) =     33.303 ms/op
     p(99.9900) =     36.962 ms/op
     p(99.9990) =     36.962 ms/op
     p(99.9999) =     36.962 ms/op
    p(100.0000) =     36.962 ms/op


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
# Warmup Iteration   1: 2.949 ±(99.9%) 0.063 ms/op
Iteration   1: 1.874 ±(99.9%) 0.026 ms/op
                 existUser·p0.00:   0.601 ms/op
                 existUser·p0.50:   1.782 ms/op
                 existUser·p0.90:   2.261 ms/op
                 existUser·p0.95:   2.454 ms/op
                 existUser·p0.99:   3.932 ms/op
                 existUser·p0.999:  19.464 ms/op
                 existUser·p0.9999: 20.490 ms/op
                 existUser·p1.00:   20.513 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17087
  mean =      1.874 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16340 
    [ 2.500,  5.000) = 680 
    [ 5.000,  7.500) = 3 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 24 
    [15.000, 17.500) = 8 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.601 ms/op
     p(50.0000) =      1.782 ms/op
     p(90.0000) =      2.261 ms/op
     p(95.0000) =      2.454 ms/op
     p(99.0000) =      3.932 ms/op
     p(99.9000) =     19.464 ms/op
     p(99.9900) =     20.490 ms/op
     p(99.9990) =     20.513 ms/op
     p(99.9999) =     20.513 ms/op
    p(100.0000) =     20.513 ms/op


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
# Warmup Iteration   1: 3.622 ±(99.9%) 0.108 ms/op
Iteration   1: 2.174 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   0.449 ms/op
                 getUser·p0.50:   2.118 ms/op
                 getUser·p0.90:   2.728 ms/op
                 getUser·p0.95:   2.941 ms/op
                 getUser·p0.99:   5.030 ms/op
                 getUser·p0.999:  12.517 ms/op
                 getUser·p0.9999: 12.644 ms/op
                 getUser·p1.00:   12.698 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14703
  mean =      2.174 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 84 
    [ 1.250,  2.500) = 11685 
    [ 2.500,  3.750) = 2721 
    [ 3.750,  5.000) = 61 
    [ 5.000,  6.250) = 118 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 2 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 16 
    [12.500, 13.750) = 16 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.449 ms/op
     p(50.0000) =      2.118 ms/op
     p(90.0000) =      2.728 ms/op
     p(95.0000) =      2.941 ms/op
     p(99.0000) =      5.030 ms/op
     p(99.9000) =     12.517 ms/op
     p(99.9900) =     12.644 ms/op
     p(99.9990) =     12.698 ms/op
     p(99.9999) =     12.698 ms/op
    p(100.0000) =     12.698 ms/op


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
# Warmup Iteration   1: 4.494 ±(99.9%) 0.127 ms/op
Iteration   1: 3.430 ±(99.9%) 0.029 ms/op
                 listUser·p0.00:   1.130 ms/op
                 listUser·p0.50:   3.486 ms/op
                 listUser·p0.90:   4.202 ms/op
                 listUser·p0.95:   4.596 ms/op
                 listUser·p0.99:   5.784 ms/op
                 listUser·p0.999:  11.087 ms/op
                 listUser·p0.9999: 11.338 ms/op
                 listUser·p1.00:   11.338 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9319
  mean =      3.430 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1 
    [ 1.250,  2.500) = 1170 
    [ 2.500,  3.750) = 4998 
    [ 3.750,  5.000) = 2964 
    [ 5.000,  6.250) = 140 
    [ 6.250,  7.500) = 14 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 27 
    [11.250, 12.500) = 5 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.130 ms/op
     p(50.0000) =      3.486 ms/op
     p(90.0000) =      4.202 ms/op
     p(95.0000) =      4.596 ms/op
     p(99.0000) =      5.784 ms/op
     p(99.9000) =     11.087 ms/op
     p(99.9900) =     11.338 ms/op
     p(99.9990) =     11.338 ms/op
     p(99.9999) =     11.338 ms/op
    p(100.0000) =     11.338 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.336          ops/ms
ClientSimple.existUser                       thrpt         14.190          ops/ms
ClientSimple.getUser                         thrpt         13.175          ops/ms
ClientSimple.listUser                        thrpt          9.617          ops/ms
ClientSimple.createUser                       avgt          2.118           ms/op
ClientSimple.existUser                        avgt          1.770           ms/op
ClientSimple.getUser                          avgt          2.046           ms/op
ClientSimple.listUser                         avgt          3.395           ms/op
ClientSimple.createUser                     sample  15220   2.100 ± 0.045   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.477           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.917           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.503           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.724           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.152           ms/op
ClientSimple.createUser:createUser·p0.999   sample         33.303           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         36.962           ms/op
ClientSimple.createUser:createUser·p1.00    sample         36.962           ms/op
ClientSimple.existUser                      sample  17087   1.874 ± 0.026   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.601           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.782           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.261           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.454           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.932           ms/op
ClientSimple.existUser:existUser·p0.999     sample         19.464           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         20.490           ms/op
ClientSimple.existUser:existUser·p1.00      sample         20.513           ms/op
ClientSimple.getUser                        sample  14703   2.174 ± 0.020   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.449           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.118           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.728           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.941           ms/op
ClientSimple.getUser:getUser·p0.99          sample          5.030           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.517           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         12.644           ms/op
ClientSimple.getUser:getUser·p1.00          sample         12.698           ms/op
ClientSimple.listUser                       sample   9319   3.430 ± 0.029   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.130           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.486           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.202           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.596           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.784           ms/op
ClientSimple.listUser:listUser·p0.999       sample         11.087           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         11.338           ms/op
ClientSimple.listUser:listUser·p1.00        sample         11.338           ms/op

Benchmark result is saved to 1725127922706.json
