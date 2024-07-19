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
# Warmup Iteration   1: 1.130 ops/ms
Iteration   1: 6.798 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.798 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.222 ops/ms
Iteration   1: 11.596 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.596 ops/ms


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
# Warmup Iteration   1: 5.995 ops/ms
Iteration   1: 14.069 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  14.069 ops/ms


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
# Warmup Iteration   1: 5.110 ops/ms
Iteration   1: 8.920 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.920 ops/ms


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
# Warmup Iteration   1: 4.147 ±(99.9%) 0.084 ms/op
Iteration   1: 1.999 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  1.999 ms/op


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
# Warmup Iteration   1: 3.289 ±(99.9%) 0.060 ms/op
Iteration   1: 1.983 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.983 ms/op


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
# Warmup Iteration   1: 3.612 ±(99.9%) 0.076 ms/op
Iteration   1: 1.928 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.928 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 5.352 ±(99.9%) 0.131 ms/op
Iteration   1: 3.592 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.592 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 3.513 ±(99.9%) 0.090 ms/op
Iteration   1: 2.271 ±(99.9%) 0.043 ms/op
                 createUser·p0.00:   0.370 ms/op
                 createUser·p0.50:   2.105 ms/op
                 createUser·p0.90:   2.740 ms/op
                 createUser·p0.95:   2.986 ms/op
                 createUser·p0.99:   5.661 ms/op
                 createUser·p0.999:  30.212 ms/op
                 createUser·p0.9999: 30.598 ms/op
                 createUser·p1.00:   30.638 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14076
  mean =      2.271 ±(99.9%) 0.043 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11412 
    [ 2.500,  5.000) = 2472 
    [ 5.000,  7.500) = 78 
    [ 7.500, 10.000) = 50 
    [10.000, 12.500) = 12 
    [12.500, 15.000) = 20 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 17 
    [30.000, 32.500) = 15 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.370 ms/op
     p(50.0000) =      2.105 ms/op
     p(90.0000) =      2.740 ms/op
     p(95.0000) =      2.986 ms/op
     p(99.0000) =      5.661 ms/op
     p(99.9000) =     30.212 ms/op
     p(99.9900) =     30.598 ms/op
     p(99.9990) =     30.638 ms/op
     p(99.9999) =     30.638 ms/op
    p(100.0000) =     30.638 ms/op


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
# Warmup Iteration   1: 3.357 ±(99.9%) 0.107 ms/op
Iteration   1: 1.994 ±(99.9%) 0.023 ms/op
                 existUser·p0.00:   0.596 ms/op
                 existUser·p0.50:   1.894 ms/op
                 existUser·p0.90:   2.363 ms/op
                 existUser·p0.95:   2.523 ms/op
                 existUser·p0.99:   3.672 ms/op
                 existUser·p0.999:  15.334 ms/op
                 existUser·p0.9999: 16.679 ms/op
                 existUser·p1.00:   16.679 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16339
  mean =      1.994 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 169 
    [ 1.250,  2.500) = 15280 
    [ 2.500,  3.750) = 736 
    [ 3.750,  5.000) = 25 
    [ 5.000,  6.250) = 60 
    [ 6.250,  7.500) = 5 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 13 
    [13.750, 15.000) = 33 
    [15.000, 16.250) = 6 
    [16.250, 17.500) = 11 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.596 ms/op
     p(50.0000) =      1.894 ms/op
     p(90.0000) =      2.363 ms/op
     p(95.0000) =      2.523 ms/op
     p(99.0000) =      3.672 ms/op
     p(99.9000) =     15.334 ms/op
     p(99.9900) =     16.679 ms/op
     p(99.9990) =     16.679 ms/op
     p(99.9999) =     16.679 ms/op
    p(100.0000) =     16.679 ms/op


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
# Warmup Iteration   1: 3.294 ±(99.9%) 0.082 ms/op
Iteration   1: 2.093 ±(99.9%) 0.034 ms/op
                 getUser·p0.00:   0.708 ms/op
                 getUser·p0.50:   1.937 ms/op
                 getUser·p0.90:   2.635 ms/op
                 getUser·p0.95:   2.937 ms/op
                 getUser·p0.99:   6.257 ms/op
                 getUser·p0.999:  22.446 ms/op
                 getUser·p0.9999: 25.960 ms/op
                 getUser·p1.00:   29.262 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15416
  mean =      2.093 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13205 
    [ 2.500,  5.000) = 2023 
    [ 5.000,  7.500) = 59 
    [ 7.500, 10.000) = 65 
    [10.000, 12.500) = 1 
    [12.500, 15.000) = 31 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.708 ms/op
     p(50.0000) =      1.937 ms/op
     p(90.0000) =      2.635 ms/op
     p(95.0000) =      2.937 ms/op
     p(99.0000) =      6.257 ms/op
     p(99.9000) =     22.446 ms/op
     p(99.9900) =     25.960 ms/op
     p(99.9990) =     29.262 ms/op
     p(99.9999) =     29.262 ms/op
    p(100.0000) =     29.262 ms/op


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
# Warmup Iteration   1: 4.394 ±(99.9%) 0.122 ms/op
Iteration   1: 3.071 ±(99.9%) 0.047 ms/op
                 listUser·p0.00:   1.075 ms/op
                 listUser·p0.50:   2.830 ms/op
                 listUser·p0.90:   3.647 ms/op
                 listUser·p0.95:   3.928 ms/op
                 listUser·p0.99:   6.070 ms/op
                 listUser·p0.999:  24.103 ms/op
                 listUser·p0.9999: 25.197 ms/op
                 listUser·p1.00:   25.199 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10404
  mean =      3.071 ±(99.9%) 0.047 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 299 
    [ 2.500,  5.000) = 9956 
    [ 5.000,  7.500) = 85 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      1.075 ms/op
     p(50.0000) =      2.830 ms/op
     p(90.0000) =      3.647 ms/op
     p(95.0000) =      3.928 ms/op
     p(99.0000) =      6.070 ms/op
     p(99.9000) =     24.103 ms/op
     p(99.9900) =     25.197 ms/op
     p(99.9990) =     25.199 ms/op
     p(99.9999) =     25.199 ms/op
    p(100.0000) =     25.199 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.798          ops/ms
ClientSimple.existUser                       thrpt         11.596          ops/ms
ClientSimple.getUser                         thrpt         14.069          ops/ms
ClientSimple.listUser                        thrpt          8.920          ops/ms
ClientSimple.createUser                       avgt          1.999           ms/op
ClientSimple.existUser                        avgt          1.983           ms/op
ClientSimple.getUser                          avgt          1.928           ms/op
ClientSimple.listUser                         avgt          3.592           ms/op
ClientSimple.createUser                     sample  14076   2.271 ± 0.043   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.370           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.105           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.740           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.986           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.661           ms/op
ClientSimple.createUser:createUser·p0.999   sample         30.212           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         30.598           ms/op
ClientSimple.createUser:createUser·p1.00    sample         30.638           ms/op
ClientSimple.existUser                      sample  16339   1.994 ± 0.023   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.596           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.894           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.363           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.523           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.672           ms/op
ClientSimple.existUser:existUser·p0.999     sample         15.334           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         16.679           ms/op
ClientSimple.existUser:existUser·p1.00      sample         16.679           ms/op
ClientSimple.getUser                        sample  15416   2.093 ± 0.034   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.708           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.937           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.635           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.937           ms/op
ClientSimple.getUser:getUser·p0.99          sample          6.257           ms/op
ClientSimple.getUser:getUser·p0.999         sample         22.446           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         25.960           ms/op
ClientSimple.getUser:getUser·p1.00          sample         29.262           ms/op
ClientSimple.listUser                       sample  10404   3.071 ± 0.047   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.075           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.830           ms/op
ClientSimple.listUser:listUser·p0.90        sample          3.647           ms/op
ClientSimple.listUser:listUser·p0.95        sample          3.928           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.070           ms/op
ClientSimple.listUser:listUser·p0.999       sample         24.103           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         25.197           ms/op
ClientSimple.listUser:listUser·p1.00        sample         25.199           ms/op

Benchmark result is saved to 1721391398813.json
