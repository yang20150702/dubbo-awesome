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
# Warmup Iteration   1: 1.966 ops/ms
Iteration   1: 7.099 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.099 ops/ms


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
# Warmup Iteration   1: 5.394 ops/ms
Iteration   1: 12.759 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.759 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.352 ops/ms
Iteration   1: 12.956 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.956 ops/ms


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
# Warmup Iteration   1: 4.967 ops/ms
Iteration   1: 8.502 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.502 ops/ms


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
# Warmup Iteration   1: 4.047 ±(99.9%) 0.075 ms/op
Iteration   1: 2.173 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.173 ms/op


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
# Warmup Iteration   1: 3.207 ±(99.9%) 0.051 ms/op
Iteration   1: 2.026 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.026 ms/op


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
# Warmup Iteration   1: 3.317 ±(99.9%) 0.059 ms/op
Iteration   1: 2.075 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.075 ms/op


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
# Warmup Iteration   1: 4.375 ±(99.9%) 0.098 ms/op
Iteration   1: 3.191 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.191 ms/op


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
# Warmup Iteration   1: 3.292 ±(99.9%) 0.076 ms/op
Iteration   1: 2.204 ±(99.9%) 0.076 ms/op
                 createUser·p0.00:   0.608 ms/op
                 createUser·p0.50:   1.923 ms/op
                 createUser·p0.90:   2.437 ms/op
                 createUser·p0.95:   2.777 ms/op
                 createUser·p0.99:   5.661 ms/op
                 createUser·p0.999:  58.222 ms/op
                 createUser·p0.9999: 60.198 ms/op
                 createUser·p1.00:   60.228 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14507
  mean =      2.204 ±(99.9%) 0.076 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 14311 
    [ 5.000, 10.000) = 102 
    [10.000, 15.000) = 62 
    [15.000, 20.000) = 0 
    [20.000, 25.000) = 0 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 0 
    [45.000, 50.000) = 0 
    [50.000, 55.000) = 0 
    [55.000, 60.000) = 27 
    [60.000, 65.000) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.608 ms/op
     p(50.0000) =      1.923 ms/op
     p(90.0000) =      2.437 ms/op
     p(95.0000) =      2.777 ms/op
     p(99.0000) =      5.661 ms/op
     p(99.9000) =     58.222 ms/op
     p(99.9900) =     60.198 ms/op
     p(99.9990) =     60.228 ms/op
     p(99.9999) =     60.228 ms/op
    p(100.0000) =     60.228 ms/op


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
# Warmup Iteration   1: 3.073 ±(99.9%) 0.066 ms/op
Iteration   1: 1.807 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   0.606 ms/op
                 existUser·p0.50:   1.769 ms/op
                 existUser·p0.90:   2.001 ms/op
                 existUser·p0.95:   2.220 ms/op
                 existUser·p0.99:   3.035 ms/op
                 existUser·p0.999:  12.211 ms/op
                 existUser·p0.9999: 13.078 ms/op
                 existUser·p1.00:   13.418 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17706
  mean =      1.807 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 468 
    [ 1.250,  2.500) = 16818 
    [ 2.500,  3.750) = 297 
    [ 3.750,  5.000) = 46 
    [ 5.000,  6.250) = 36 
    [ 6.250,  7.500) = 9 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 26 
    [12.500, 13.750) = 6 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.606 ms/op
     p(50.0000) =      1.769 ms/op
     p(90.0000) =      2.001 ms/op
     p(95.0000) =      2.220 ms/op
     p(99.0000) =      3.035 ms/op
     p(99.9000) =     12.211 ms/op
     p(99.9900) =     13.078 ms/op
     p(99.9990) =     13.418 ms/op
     p(99.9999) =     13.418 ms/op
    p(100.0000) =     13.418 ms/op


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
# Warmup Iteration   1: 3.239 ±(99.9%) 0.082 ms/op
Iteration   1: 2.080 ±(99.9%) 0.037 ms/op
                 getUser·p0.00:   0.485 ms/op
                 getUser·p0.50:   1.956 ms/op
                 getUser·p0.90:   2.531 ms/op
                 getUser·p0.95:   2.892 ms/op
                 getUser·p0.99:   5.120 ms/op
                 getUser·p0.999:  28.923 ms/op
                 getUser·p0.9999: 30.651 ms/op
                 getUser·p1.00:   30.704 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15354
  mean =      2.080 ±(99.9%) 0.037 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13722 
    [ 2.500,  5.000) = 1463 
    [ 5.000,  7.500) = 99 
    [ 7.500, 10.000) = 5 
    [10.000, 12.500) = 34 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 2 
    [27.500, 30.000) = 27 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.485 ms/op
     p(50.0000) =      1.956 ms/op
     p(90.0000) =      2.531 ms/op
     p(95.0000) =      2.892 ms/op
     p(99.0000) =      5.120 ms/op
     p(99.9000) =     28.923 ms/op
     p(99.9900) =     30.651 ms/op
     p(99.9990) =     30.704 ms/op
     p(99.9999) =     30.704 ms/op
    p(100.0000) =     30.704 ms/op


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
# Warmup Iteration   1: 4.646 ±(99.9%) 0.132 ms/op
Iteration   1: 3.589 ±(99.9%) 0.042 ms/op
                 listUser·p0.00:   1.059 ms/op
                 listUser·p0.50:   3.592 ms/op
                 listUser·p0.90:   4.268 ms/op
                 listUser·p0.95:   4.465 ms/op
                 listUser·p0.99:   6.012 ms/op
                 listUser·p0.999:  19.628 ms/op
                 listUser·p0.9999: 20.218 ms/op
                 listUser·p1.00:   20.218 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8907
  mean =      3.589 ±(99.9%) 0.042 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 548 
    [ 2.500,  5.000) = 8102 
    [ 5.000,  7.500) = 205 
    [ 7.500, 10.000) = 18 
    [10.000, 12.500) = 2 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.059 ms/op
     p(50.0000) =      3.592 ms/op
     p(90.0000) =      4.268 ms/op
     p(95.0000) =      4.465 ms/op
     p(99.0000) =      6.012 ms/op
     p(99.9000) =     19.628 ms/op
     p(99.9900) =     20.218 ms/op
     p(99.9990) =     20.218 ms/op
     p(99.9999) =     20.218 ms/op
    p(100.0000) =     20.218 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.099          ops/ms
ClientSimple.existUser                       thrpt         12.759          ops/ms
ClientSimple.getUser                         thrpt         12.956          ops/ms
ClientSimple.listUser                        thrpt          8.502          ops/ms
ClientSimple.createUser                       avgt          2.173           ms/op
ClientSimple.existUser                        avgt          2.026           ms/op
ClientSimple.getUser                          avgt          2.075           ms/op
ClientSimple.listUser                         avgt          3.191           ms/op
ClientSimple.createUser                     sample  14507   2.204 ± 0.076   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.608           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.923           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.437           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.777           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.661           ms/op
ClientSimple.createUser:createUser·p0.999   sample         58.222           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         60.198           ms/op
ClientSimple.createUser:createUser·p1.00    sample         60.228           ms/op
ClientSimple.existUser                      sample  17706   1.807 ± 0.014   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.606           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.769           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.001           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.220           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.035           ms/op
ClientSimple.existUser:existUser·p0.999     sample         12.211           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         13.078           ms/op
ClientSimple.existUser:existUser·p1.00      sample         13.418           ms/op
ClientSimple.getUser                        sample  15354   2.080 ± 0.037   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.485           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.956           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.531           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.892           ms/op
ClientSimple.getUser:getUser·p0.99          sample          5.120           ms/op
ClientSimple.getUser:getUser·p0.999         sample         28.923           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         30.651           ms/op
ClientSimple.getUser:getUser·p1.00          sample         30.704           ms/op
ClientSimple.listUser                       sample   8907   3.589 ± 0.042   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.059           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.592           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.268           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.465           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.012           ms/op
ClientSimple.listUser:listUser·p0.999       sample         19.628           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         20.218           ms/op
ClientSimple.listUser:listUser·p1.00        sample         20.218           ms/op

Benchmark result is saved to 1720635194198.json
