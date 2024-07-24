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
# Warmup Iteration   1: 1.792 ops/ms
Iteration   1: 6.877 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.877 ops/ms


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
# Warmup Iteration   1: 5.509 ops/ms
Iteration   1: 12.865 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.865 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 5.094 ops/ms
Iteration   1: 11.764 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.764 ops/ms


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
# Warmup Iteration   1: 6.176 ops/ms
Iteration   1: 9.787 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.787 ops/ms


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
# Warmup Iteration   1: 3.847 ±(99.9%) 0.064 ms/op
Iteration   1: 2.245 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.245 ms/op


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
# Warmup Iteration   1: 2.900 ±(99.9%) 0.049 ms/op
Iteration   1: 1.841 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.841 ms/op


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
# Warmup Iteration   1: 3.060 ±(99.9%) 0.053 ms/op
Iteration   1: 2.571 ±(99.9%) 0.025 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.571 ms/op


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
# Warmup Iteration   1: 4.254 ±(99.9%) 0.081 ms/op
Iteration   1: 3.178 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.178 ms/op


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
# Warmup Iteration   1: 3.586 ±(99.9%) 0.089 ms/op
Iteration   1: 2.258 ±(99.9%) 0.035 ms/op
                 createUser·p0.00:   0.345 ms/op
                 createUser·p0.50:   2.095 ms/op
                 createUser·p0.90:   2.626 ms/op
                 createUser·p0.95:   2.877 ms/op
                 createUser·p0.99:   10.093 ms/op
                 createUser·p0.999:  16.220 ms/op
                 createUser·p0.9999: 16.679 ms/op
                 createUser·p1.00:   16.728 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14269
  mean =      2.258 ±(99.9%) 0.035 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 157 
    [ 1.250,  2.500) = 11952 
    [ 2.500,  3.750) = 1864 
    [ 3.750,  5.000) = 66 
    [ 5.000,  6.250) = 5 
    [ 6.250,  7.500) = 30 
    [ 7.500,  8.750) = 34 
    [ 8.750, 10.000) = 7 
    [10.000, 11.250) = 27 
    [11.250, 12.500) = 59 
    [12.500, 13.750) = 28 
    [13.750, 15.000) = 5 
    [15.000, 16.250) = 28 
    [16.250, 17.500) = 7 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.345 ms/op
     p(50.0000) =      2.095 ms/op
     p(90.0000) =      2.626 ms/op
     p(95.0000) =      2.877 ms/op
     p(99.0000) =     10.093 ms/op
     p(99.9000) =     16.220 ms/op
     p(99.9900) =     16.679 ms/op
     p(99.9990) =     16.728 ms/op
     p(99.9999) =     16.728 ms/op
    p(100.0000) =     16.728 ms/op


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
# Warmup Iteration   1: 3.089 ±(99.9%) 0.080 ms/op
Iteration   1: 1.943 ±(99.9%) 0.041 ms/op
                 existUser·p0.00:   0.323 ms/op
                 existUser·p0.50:   1.782 ms/op
                 existUser·p0.90:   2.241 ms/op
                 existUser·p0.95:   2.462 ms/op
                 existUser·p0.99:   3.805 ms/op
                 existUser·p0.999:  33.408 ms/op
                 existUser·p0.9999: 33.554 ms/op
                 existUser·p1.00:   33.554 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16484
  mean =      1.943 ±(99.9%) 0.041 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15718 
    [ 2.500,  5.000) = 669 
    [ 5.000,  7.500) = 1 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 28 
    [15.000, 17.500) = 4 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 32 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.323 ms/op
     p(50.0000) =      1.782 ms/op
     p(90.0000) =      2.241 ms/op
     p(95.0000) =      2.462 ms/op
     p(99.0000) =      3.805 ms/op
     p(99.9000) =     33.408 ms/op
     p(99.9900) =     33.554 ms/op
     p(99.9990) =     33.554 ms/op
     p(99.9999) =     33.554 ms/op
    p(100.0000) =     33.554 ms/op


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
# Warmup Iteration   1: 3.192 ±(99.9%) 0.083 ms/op
Iteration   1: 1.897 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   0.592 ms/op
                 getUser·p0.50:   1.763 ms/op
                 getUser·p0.90:   2.298 ms/op
                 getUser·p0.95:   2.482 ms/op
                 getUser·p0.99:   3.962 ms/op
                 getUser·p0.999:  10.885 ms/op
                 getUser·p0.9999: 12.423 ms/op
                 getUser·p1.00:   12.501 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16815
  mean =      1.897 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 45 
    [ 1.250,  2.500) = 15973 
    [ 2.500,  3.750) = 598 
    [ 3.750,  5.000) = 45 
    [ 5.000,  6.250) = 116 
    [ 6.250,  7.500) = 3 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 3 
    [10.000, 11.250) = 25 
    [11.250, 12.500) = 6 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.592 ms/op
     p(50.0000) =      1.763 ms/op
     p(90.0000) =      2.298 ms/op
     p(95.0000) =      2.482 ms/op
     p(99.0000) =      3.962 ms/op
     p(99.9000) =     10.885 ms/op
     p(99.9900) =     12.423 ms/op
     p(99.9990) =     12.501 ms/op
     p(99.9999) =     12.501 ms/op
    p(100.0000) =     12.501 ms/op


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
# Warmup Iteration   1: 4.538 ±(99.9%) 0.146 ms/op
Iteration   1: 3.256 ±(99.9%) 0.041 ms/op
                 listUser·p0.00:   0.775 ms/op
                 listUser·p0.50:   3.039 ms/op
                 listUser·p0.90:   4.141 ms/op
                 listUser·p0.95:   4.465 ms/op
                 listUser·p0.99:   7.168 ms/op
                 listUser·p0.999:  19.343 ms/op
                 listUser·p0.9999: 28.213 ms/op
                 listUser·p1.00:   28.213 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9811
  mean =      3.256 ±(99.9%) 0.041 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1620 
    [ 2.500,  5.000) = 7959 
    [ 5.000,  7.500) = 158 
    [ 7.500, 10.000) = 26 
    [10.000, 12.500) = 16 
    [12.500, 15.000) = 3 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.775 ms/op
     p(50.0000) =      3.039 ms/op
     p(90.0000) =      4.141 ms/op
     p(95.0000) =      4.465 ms/op
     p(99.0000) =      7.168 ms/op
     p(99.9000) =     19.343 ms/op
     p(99.9900) =     28.213 ms/op
     p(99.9990) =     28.213 ms/op
     p(99.9999) =     28.213 ms/op
    p(100.0000) =     28.213 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.877          ops/ms
ClientSimple.existUser                       thrpt         12.865          ops/ms
ClientSimple.getUser                         thrpt         11.764          ops/ms
ClientSimple.listUser                        thrpt          9.787          ops/ms
ClientSimple.createUser                       avgt          2.245           ms/op
ClientSimple.existUser                        avgt          1.841           ms/op
ClientSimple.getUser                          avgt          2.571           ms/op
ClientSimple.listUser                         avgt          3.178           ms/op
ClientSimple.createUser                     sample  14269   2.258 ± 0.035   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.345           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.095           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.626           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.877           ms/op
ClientSimple.createUser:createUser·p0.99    sample         10.093           ms/op
ClientSimple.createUser:createUser·p0.999   sample         16.220           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         16.679           ms/op
ClientSimple.createUser:createUser·p1.00    sample         16.728           ms/op
ClientSimple.existUser                      sample  16484   1.943 ± 0.041   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.323           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.782           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.241           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.462           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.805           ms/op
ClientSimple.existUser:existUser·p0.999     sample         33.408           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         33.554           ms/op
ClientSimple.existUser:existUser·p1.00      sample         33.554           ms/op
ClientSimple.getUser                        sample  16815   1.897 ± 0.016   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.592           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.763           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.298           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.482           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.962           ms/op
ClientSimple.getUser:getUser·p0.999         sample         10.885           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         12.423           ms/op
ClientSimple.getUser:getUser·p1.00          sample         12.501           ms/op
ClientSimple.listUser                       sample   9811   3.256 ± 0.041   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.775           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.039           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.141           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.465           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.168           ms/op
ClientSimple.listUser:listUser·p0.999       sample         19.343           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         28.213           ms/op
ClientSimple.listUser:listUser·p1.00        sample         28.213           ms/op

Benchmark result is saved to 1721844785721.json
