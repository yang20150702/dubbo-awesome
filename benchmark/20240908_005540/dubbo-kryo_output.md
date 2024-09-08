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
# Warmup Iteration   1: 1.715 ops/ms
Iteration   1: 7.162 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.162 ops/ms


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
# Warmup Iteration   1: 6.554 ops/ms
Iteration   1: 14.451 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  14.451 ops/ms


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
# Warmup Iteration   1: 6.035 ops/ms
Iteration   1: 15.166 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  15.166 ops/ms


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
# Warmup Iteration   1: 5.516 ops/ms
Iteration   1: 9.023 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.023 ops/ms


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
# Warmup Iteration   1: 3.980 ±(99.9%) 0.088 ms/op
Iteration   1: 2.152 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.152 ms/op


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
# Warmup Iteration   1: 3.163 ±(99.9%) 0.051 ms/op
Iteration   1: 1.908 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.908 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 2.994 ±(99.9%) 0.048 ms/op
Iteration   1: 2.085 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.085 ms/op


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
# Warmup Iteration   1: 4.462 ±(99.9%) 0.089 ms/op
Iteration   1: 3.517 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.517 ms/op


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
# Warmup Iteration   1: 3.823 ±(99.9%) 0.111 ms/op
Iteration   1: 2.273 ±(99.9%) 0.050 ms/op
                 createUser·p0.00:   0.494 ms/op
                 createUser·p0.50:   2.071 ms/op
                 createUser·p0.90:   2.523 ms/op
                 createUser·p0.95:   2.720 ms/op
                 createUser·p0.99:   10.196 ms/op
                 createUser·p0.999:  27.001 ms/op
                 createUser·p0.9999: 27.263 ms/op
                 createUser·p1.00:   27.263 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14069
  mean =      2.273 ±(99.9%) 0.050 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12525 
    [ 2.500,  5.000) = 1301 
    [ 5.000,  7.500) = 51 
    [ 7.500, 10.000) = 32 
    [10.000, 12.500) = 68 
    [12.500, 15.000) = 27 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.494 ms/op
     p(50.0000) =      2.071 ms/op
     p(90.0000) =      2.523 ms/op
     p(95.0000) =      2.720 ms/op
     p(99.0000) =     10.196 ms/op
     p(99.9000) =     27.001 ms/op
     p(99.9900) =     27.263 ms/op
     p(99.9990) =     27.263 ms/op
     p(99.9999) =     27.263 ms/op
    p(100.0000) =     27.263 ms/op


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
# Warmup Iteration   1: 2.590 ±(99.9%) 0.056 ms/op
Iteration   1: 2.279 ±(99.9%) 0.150 ms/op
                 existUser·p0.00:   0.487 ms/op
                 existUser·p0.50:   1.802 ms/op
                 existUser·p0.90:   2.515 ms/op
                 existUser·p0.95:   2.707 ms/op
                 existUser·p0.99:   5.841 ms/op
                 existUser·p0.999:  107.479 ms/op
                 existUser·p0.9999: 110.780 ms/op
                 existUser·p1.00:   111.149 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 14021
  mean =      2.279 ±(99.9%) 0.150 ms/op

  Histogram, ms/op:
    [  0.000,  12.500) = 13921 
    [ 12.500,  25.000) = 36 
    [ 25.000,  37.500) = 9 
    [ 37.500,  50.000) = 23 
    [ 50.000,  62.500) = 0 
    [ 62.500,  75.000) = 0 
    [ 75.000,  87.500) = 0 
    [ 87.500, 100.000) = 0 
    [100.000, 112.500) = 32 
    [112.500, 125.000) = 0 
    [125.000, 137.500) = 0 
    [137.500, 150.000) = 0 
    [150.000, 162.500) = 0 
    [162.500, 175.000) = 0 
    [175.000, 187.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.487 ms/op
     p(50.0000) =      1.802 ms/op
     p(90.0000) =      2.515 ms/op
     p(95.0000) =      2.707 ms/op
     p(99.0000) =      5.841 ms/op
     p(99.9000) =    107.479 ms/op
     p(99.9900) =    110.780 ms/op
     p(99.9990) =    111.149 ms/op
     p(99.9999) =    111.149 ms/op
    p(100.0000) =    111.149 ms/op


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
# Warmup Iteration   1: 3.395 ±(99.9%) 0.089 ms/op
Iteration   1: 2.061 ±(99.9%) 0.026 ms/op
                 getUser·p0.00:   1.002 ms/op
                 getUser·p0.50:   1.903 ms/op
                 getUser·p0.90:   2.441 ms/op
                 getUser·p0.95:   2.691 ms/op
                 getUser·p0.99:   3.908 ms/op
                 getUser·p0.999:  20.382 ms/op
                 getUser·p0.9999: 21.004 ms/op
                 getUser·p1.00:   21.004 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15491
  mean =      2.061 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14212 
    [ 2.500,  5.000) = 1148 
    [ 5.000,  7.500) = 73 
    [ 7.500, 10.000) = 26 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.002 ms/op
     p(50.0000) =      1.903 ms/op
     p(90.0000) =      2.441 ms/op
     p(95.0000) =      2.691 ms/op
     p(99.0000) =      3.908 ms/op
     p(99.9000) =     20.382 ms/op
     p(99.9900) =     21.004 ms/op
     p(99.9990) =     21.004 ms/op
     p(99.9999) =     21.004 ms/op
    p(100.0000) =     21.004 ms/op


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
# Warmup Iteration   1: 4.531 ±(99.9%) 0.147 ms/op
Iteration   1: 3.502 ±(99.9%) 0.059 ms/op
                 listUser·p0.00:   0.715 ms/op
                 listUser·p0.50:   3.490 ms/op
                 listUser·p0.90:   4.325 ms/op
                 listUser·p0.95:   4.686 ms/op
                 listUser·p0.99:   6.038 ms/op
                 listUser·p0.999:  29.426 ms/op
                 listUser·p0.9999: 30.736 ms/op
                 listUser·p1.00:   30.736 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9171
  mean =      3.502 ±(99.9%) 0.059 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1560 
    [ 2.500,  5.000) = 7346 
    [ 5.000,  7.500) = 198 
    [ 7.500, 10.000) = 35 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 3 
    [27.500, 30.000) = 27 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.715 ms/op
     p(50.0000) =      3.490 ms/op
     p(90.0000) =      4.325 ms/op
     p(95.0000) =      4.686 ms/op
     p(99.0000) =      6.038 ms/op
     p(99.9000) =     29.426 ms/op
     p(99.9900) =     30.736 ms/op
     p(99.9990) =     30.736 ms/op
     p(99.9999) =     30.736 ms/op
    p(100.0000) =     30.736 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt    Score   Error   Units
ClientSimple.createUser                      thrpt           7.162          ops/ms
ClientSimple.existUser                       thrpt          14.451          ops/ms
ClientSimple.getUser                         thrpt          15.166          ops/ms
ClientSimple.listUser                        thrpt           9.023          ops/ms
ClientSimple.createUser                       avgt           2.152           ms/op
ClientSimple.existUser                        avgt           1.908           ms/op
ClientSimple.getUser                          avgt           2.085           ms/op
ClientSimple.listUser                         avgt           3.517           ms/op
ClientSimple.createUser                     sample  14069    2.273 ± 0.050   ms/op
ClientSimple.createUser:createUser·p0.00    sample           0.494           ms/op
ClientSimple.createUser:createUser·p0.50    sample           2.071           ms/op
ClientSimple.createUser:createUser·p0.90    sample           2.523           ms/op
ClientSimple.createUser:createUser·p0.95    sample           2.720           ms/op
ClientSimple.createUser:createUser·p0.99    sample          10.196           ms/op
ClientSimple.createUser:createUser·p0.999   sample          27.001           ms/op
ClientSimple.createUser:createUser·p0.9999  sample          27.263           ms/op
ClientSimple.createUser:createUser·p1.00    sample          27.263           ms/op
ClientSimple.existUser                      sample  14021    2.279 ± 0.150   ms/op
ClientSimple.existUser:existUser·p0.00      sample           0.487           ms/op
ClientSimple.existUser:existUser·p0.50      sample           1.802           ms/op
ClientSimple.existUser:existUser·p0.90      sample           2.515           ms/op
ClientSimple.existUser:existUser·p0.95      sample           2.707           ms/op
ClientSimple.existUser:existUser·p0.99      sample           5.841           ms/op
ClientSimple.existUser:existUser·p0.999     sample         107.479           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         110.780           ms/op
ClientSimple.existUser:existUser·p1.00      sample         111.149           ms/op
ClientSimple.getUser                        sample  15491    2.061 ± 0.026   ms/op
ClientSimple.getUser:getUser·p0.00          sample           1.002           ms/op
ClientSimple.getUser:getUser·p0.50          sample           1.903           ms/op
ClientSimple.getUser:getUser·p0.90          sample           2.441           ms/op
ClientSimple.getUser:getUser·p0.95          sample           2.691           ms/op
ClientSimple.getUser:getUser·p0.99          sample           3.908           ms/op
ClientSimple.getUser:getUser·p0.999         sample          20.382           ms/op
ClientSimple.getUser:getUser·p0.9999        sample          21.004           ms/op
ClientSimple.getUser:getUser·p1.00          sample          21.004           ms/op
ClientSimple.listUser                       sample   9171    3.502 ± 0.059   ms/op
ClientSimple.listUser:listUser·p0.00        sample           0.715           ms/op
ClientSimple.listUser:listUser·p0.50        sample           3.490           ms/op
ClientSimple.listUser:listUser·p0.90        sample           4.325           ms/op
ClientSimple.listUser:listUser·p0.95        sample           4.686           ms/op
ClientSimple.listUser:listUser·p0.99        sample           6.038           ms/op
ClientSimple.listUser:listUser·p0.999       sample          29.426           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          30.736           ms/op
ClientSimple.listUser:listUser·p1.00        sample          30.736           ms/op

Benchmark result is saved to 1725756680804.json
