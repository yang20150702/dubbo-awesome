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
# Warmup Iteration   1: 1.946 ops/ms
Iteration   1: 7.062 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.062 ops/ms


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
# Warmup Iteration   1: 6.976 ops/ms
Iteration   1: 11.922 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.922 ops/ms


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
# Warmup Iteration   1: 5.468 ops/ms
Iteration   1: 13.592 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.592 ops/ms


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
# Warmup Iteration   1: 3.786 ops/ms
Iteration   1: 8.149 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.149 ops/ms


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
# Warmup Iteration   1: 3.526 ±(99.9%) 0.062 ms/op
Iteration   1: 2.183 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.183 ms/op


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
# Warmup Iteration   1: 3.201 ±(99.9%) 0.049 ms/op
Iteration   1: 1.849 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.849 ms/op


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
# Warmup Iteration   1: 3.397 ±(99.9%) 0.061 ms/op
Iteration   1: 1.956 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.956 ms/op


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
# Warmup Iteration   1: 5.058 ±(99.9%) 0.108 ms/op
Iteration   1: 3.744 ±(99.9%) 0.023 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.744 ms/op


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
# Warmup Iteration   1: 3.356 ±(99.9%) 0.081 ms/op
Iteration   1: 2.376 ±(99.9%) 0.031 ms/op
                 createUser·p0.00:   0.717 ms/op
                 createUser·p0.50:   2.265 ms/op
                 createUser·p0.90:   2.793 ms/op
                 createUser·p0.95:   2.945 ms/op
                 createUser·p0.99:   5.494 ms/op
                 createUser·p0.999:  20.956 ms/op
                 createUser·p0.9999: 21.274 ms/op
                 createUser·p1.00:   21.365 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13466
  mean =      2.376 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9438 
    [ 2.500,  5.000) = 3858 
    [ 5.000,  7.500) = 106 
    [ 7.500, 10.000) = 30 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 2 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 13 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.717 ms/op
     p(50.0000) =      2.265 ms/op
     p(90.0000) =      2.793 ms/op
     p(95.0000) =      2.945 ms/op
     p(99.0000) =      5.494 ms/op
     p(99.9000) =     20.956 ms/op
     p(99.9900) =     21.274 ms/op
     p(99.9990) =     21.365 ms/op
     p(99.9999) =     21.365 ms/op
    p(100.0000) =     21.365 ms/op


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
# Warmup Iteration   1: 2.991 ±(99.9%) 0.071 ms/op
Iteration   1: 2.083 ±(99.9%) 0.032 ms/op
                 existUser·p0.00:   0.843 ms/op
                 existUser·p0.50:   1.958 ms/op
                 existUser·p0.90:   2.544 ms/op
                 existUser·p0.95:   2.789 ms/op
                 existUser·p0.99:   3.203 ms/op
                 existUser·p0.999:  25.985 ms/op
                 existUser·p0.9999: 26.426 ms/op
                 existUser·p1.00:   26.444 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15504
  mean =      2.083 ±(99.9%) 0.032 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13784 
    [ 2.500,  5.000) = 1656 
    [ 5.000,  7.500) = 0 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.843 ms/op
     p(50.0000) =      1.958 ms/op
     p(90.0000) =      2.544 ms/op
     p(95.0000) =      2.789 ms/op
     p(99.0000) =      3.203 ms/op
     p(99.9000) =     25.985 ms/op
     p(99.9900) =     26.426 ms/op
     p(99.9990) =     26.444 ms/op
     p(99.9999) =     26.444 ms/op
    p(100.0000) =     26.444 ms/op


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
# Warmup Iteration   1: 3.278 ±(99.9%) 0.082 ms/op
Iteration   1: 1.937 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.017 ms/op
                 getUser·p0.50:   1.817 ms/op
                 getUser·p0.90:   2.343 ms/op
                 getUser·p0.95:   2.527 ms/op
                 getUser·p0.99:   3.882 ms/op
                 getUser·p0.999:  10.314 ms/op
                 getUser·p0.9999: 10.983 ms/op
                 getUser·p1.00:   10.994 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16508
  mean =      1.937 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 1.000,  2.000) = 11718 
    [ 2.000,  3.000) = 4522 
    [ 3.000,  4.000) = 133 
    [ 4.000,  5.000) = 103 
    [ 5.000,  6.000) = 0 
    [ 6.000,  7.000) = 0 
    [ 7.000,  8.000) = 0 
    [ 8.000,  9.000) = 0 
    [ 9.000, 10.000) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.017 ms/op
     p(50.0000) =      1.817 ms/op
     p(90.0000) =      2.343 ms/op
     p(95.0000) =      2.527 ms/op
     p(99.0000) =      3.882 ms/op
     p(99.9000) =     10.314 ms/op
     p(99.9900) =     10.983 ms/op
     p(99.9990) =     10.994 ms/op
     p(99.9999) =     10.994 ms/op
    p(100.0000) =     10.994 ms/op


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
# Warmup Iteration   1: 4.616 ±(99.9%) 0.137 ms/op
Iteration   1: 3.543 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   1.200 ms/op
                 listUser·p0.50:   3.555 ms/op
                 listUser·p0.90:   4.456 ms/op
                 listUser·p0.95:   4.710 ms/op
                 listUser·p0.99:   5.380 ms/op
                 listUser·p0.999:  7.553 ms/op
                 listUser·p0.9999: 8.798 ms/op
                 listUser·p1.00:   8.798 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9027
  mean =      3.543 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [1.000, 1.500) = 1 
    [1.500, 2.000) = 77 
    [2.000, 2.500) = 260 
    [2.500, 3.000) = 2408 
    [3.000, 3.500) = 1546 
    [3.500, 4.000) = 2109 
    [4.000, 4.500) = 1807 
    [4.500, 5.000) = 599 
    [5.000, 5.500) = 162 
    [5.500, 6.000) = 38 
    [6.000, 6.500) = 7 
    [6.500, 7.000) = 2 
    [7.000, 7.500) = 1 
    [7.500, 8.000) = 7 
    [8.000, 8.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.200 ms/op
     p(50.0000) =      3.555 ms/op
     p(90.0000) =      4.456 ms/op
     p(95.0000) =      4.710 ms/op
     p(99.0000) =      5.380 ms/op
     p(99.9000) =      7.553 ms/op
     p(99.9900) =      8.798 ms/op
     p(99.9990) =      8.798 ms/op
     p(99.9999) =      8.798 ms/op
    p(100.0000) =      8.798 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.062          ops/ms
ClientSimple.existUser                       thrpt         11.922          ops/ms
ClientSimple.getUser                         thrpt         13.592          ops/ms
ClientSimple.listUser                        thrpt          8.149          ops/ms
ClientSimple.createUser                       avgt          2.183           ms/op
ClientSimple.existUser                        avgt          1.849           ms/op
ClientSimple.getUser                          avgt          1.956           ms/op
ClientSimple.listUser                         avgt          3.744           ms/op
ClientSimple.createUser                     sample  13466   2.376 ± 0.031   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.717           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.265           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.793           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.945           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.494           ms/op
ClientSimple.createUser:createUser·p0.999   sample         20.956           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         21.274           ms/op
ClientSimple.createUser:createUser·p1.00    sample         21.365           ms/op
ClientSimple.existUser                      sample  15504   2.083 ± 0.032   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.843           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.958           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.544           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.789           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.203           ms/op
ClientSimple.existUser:existUser·p0.999     sample         25.985           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         26.426           ms/op
ClientSimple.existUser:existUser·p1.00      sample         26.444           ms/op
ClientSimple.getUser                        sample  16508   1.937 ± 0.014   ms/op
ClientSimple.getUser:getUser·p0.00          sample          1.017           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.817           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.343           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.527           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.882           ms/op
ClientSimple.getUser:getUser·p0.999         sample         10.314           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         10.983           ms/op
ClientSimple.getUser:getUser·p1.00          sample         10.994           ms/op
ClientSimple.listUser                       sample   9027   3.543 ± 0.025   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.200           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.555           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.456           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.710           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.380           ms/op
ClientSimple.listUser:listUser·p0.999       sample          7.553           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          8.798           ms/op
ClientSimple.listUser:listUser·p1.00        sample          8.798           ms/op

Benchmark result is saved to 1723745604633.json
