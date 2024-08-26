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
# Warmup Iteration   1: 1.794 ops/ms
Iteration   1: 6.549 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.549 ops/ms


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
# Warmup Iteration   1: 6.719 ops/ms
Iteration   1: 13.352 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.352 ops/ms


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
# Warmup Iteration   1: 5.865 ops/ms
Iteration   1: 13.890 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.890 ops/ms


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
# Warmup Iteration   1: 4.604 ops/ms
Iteration   1: 8.888 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.888 ops/ms


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
# Warmup Iteration   1: 3.685 ±(99.9%) 0.062 ms/op
Iteration   1: 2.308 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.308 ms/op


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
# Warmup Iteration   1: 3.111 ±(99.9%) 0.046 ms/op
Iteration   1: 1.723 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.723 ms/op


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
# Warmup Iteration   1: 3.454 ±(99.9%) 0.066 ms/op
Iteration   1: 2.115 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.115 ms/op


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
# Warmup Iteration   1: 4.314 ±(99.9%) 0.109 ms/op
Iteration   1: 3.370 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.370 ms/op


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
# Warmup Iteration   1: 3.781 ±(99.9%) 0.098 ms/op
Iteration   1: 2.037 ±(99.9%) 0.030 ms/op
                 createUser·p0.00:   0.762 ms/op
                 createUser·p0.50:   1.860 ms/op
                 createUser·p0.90:   2.458 ms/op
                 createUser·p0.95:   2.708 ms/op
                 createUser·p0.99:   6.842 ms/op
                 createUser·p0.999:  16.340 ms/op
                 createUser·p0.9999: 17.770 ms/op
                 createUser·p1.00:   17.826 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15675
  mean =      2.037 ±(99.9%) 0.030 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 289 
    [ 1.250,  2.500) = 14009 
    [ 2.500,  3.750) = 960 
    [ 3.750,  5.000) = 208 
    [ 5.000,  6.250) = 43 
    [ 6.250,  7.500) = 35 
    [ 7.500,  8.750) = 22 
    [ 8.750, 10.000) = 14 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 26 
    [12.500, 13.750) = 26 
    [13.750, 15.000) = 10 
    [15.000, 16.250) = 14 
    [16.250, 17.500) = 17 
    [17.500, 18.750) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.762 ms/op
     p(50.0000) =      1.860 ms/op
     p(90.0000) =      2.458 ms/op
     p(95.0000) =      2.708 ms/op
     p(99.0000) =      6.842 ms/op
     p(99.9000) =     16.340 ms/op
     p(99.9900) =     17.770 ms/op
     p(99.9990) =     17.826 ms/op
     p(99.9999) =     17.826 ms/op
    p(100.0000) =     17.826 ms/op


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
# Warmup Iteration   1: 3.098 ±(99.9%) 0.070 ms/op
Iteration   1: 2.100 ±(99.9%) 0.034 ms/op
                 existUser·p0.00:   0.461 ms/op
                 existUser·p0.50:   1.915 ms/op
                 existUser·p0.90:   2.580 ms/op
                 existUser·p0.95:   2.815 ms/op
                 existUser·p0.99:   5.034 ms/op
                 existUser·p0.999:  20.873 ms/op
                 existUser·p0.9999: 22.003 ms/op
                 existUser·p1.00:   22.020 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15254
  mean =      2.100 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13137 
    [ 2.500,  5.000) = 1958 
    [ 5.000,  7.500) = 54 
    [ 7.500, 10.000) = 8 
    [10.000, 12.500) = 1 
    [12.500, 15.000) = 48 
    [15.000, 17.500) = 16 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.461 ms/op
     p(50.0000) =      1.915 ms/op
     p(90.0000) =      2.580 ms/op
     p(95.0000) =      2.815 ms/op
     p(99.0000) =      5.034 ms/op
     p(99.9000) =     20.873 ms/op
     p(99.9900) =     22.003 ms/op
     p(99.9990) =     22.020 ms/op
     p(99.9999) =     22.020 ms/op
    p(100.0000) =     22.020 ms/op


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
# Warmup Iteration   1: 3.363 ±(99.9%) 0.097 ms/op
Iteration   1: 2.011 ±(99.9%) 0.036 ms/op
                 getUser·p0.00:   0.530 ms/op
                 getUser·p0.50:   1.843 ms/op
                 getUser·p0.90:   2.351 ms/op
                 getUser·p0.95:   2.531 ms/op
                 getUser·p0.99:   5.079 ms/op
                 getUser·p0.999:  24.805 ms/op
                 getUser·p0.9999: 27.916 ms/op
                 getUser·p1.00:   28.574 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15903
  mean =      2.011 ±(99.9%) 0.036 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15033 
    [ 2.500,  5.000) = 706 
    [ 5.000,  7.500) = 99 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      0.530 ms/op
     p(50.0000) =      1.843 ms/op
     p(90.0000) =      2.351 ms/op
     p(95.0000) =      2.531 ms/op
     p(99.0000) =      5.079 ms/op
     p(99.9000) =     24.805 ms/op
     p(99.9900) =     27.916 ms/op
     p(99.9990) =     28.574 ms/op
     p(99.9999) =     28.574 ms/op
    p(100.0000) =     28.574 ms/op


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
# Warmup Iteration   1: 4.494 ±(99.9%) 0.142 ms/op
Iteration   1: 3.597 ±(99.9%) 0.046 ms/op
                 listUser·p0.00:   0.952 ms/op
                 listUser·p0.50:   3.359 ms/op
                 listUser·p0.90:   4.407 ms/op
                 listUser·p0.95:   5.014 ms/op
                 listUser·p0.99:   8.733 ms/op
                 listUser·p0.999:  18.058 ms/op
                 listUser·p0.9999: 19.890 ms/op
                 listUser·p1.00:   19.890 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8899
  mean =      3.597 ±(99.9%) 0.046 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 5 
    [ 1.250,  2.500) = 313 
    [ 2.500,  3.750) = 5653 
    [ 3.750,  5.000) = 2480 
    [ 5.000,  6.250) = 235 
    [ 6.250,  7.500) = 102 
    [ 7.500,  8.750) = 24 
    [ 8.750, 10.000) = 21 
    [10.000, 11.250) = 7 
    [11.250, 12.500) = 2 
    [12.500, 13.750) = 16 
    [13.750, 15.000) = 8 
    [15.000, 16.250) = 3 
    [16.250, 17.500) = 13 
    [17.500, 18.750) = 15 

  Percentiles, ms/op:
      p(0.0000) =      0.952 ms/op
     p(50.0000) =      3.359 ms/op
     p(90.0000) =      4.407 ms/op
     p(95.0000) =      5.014 ms/op
     p(99.0000) =      8.733 ms/op
     p(99.9000) =     18.058 ms/op
     p(99.9900) =     19.890 ms/op
     p(99.9990) =     19.890 ms/op
     p(99.9999) =     19.890 ms/op
    p(100.0000) =     19.890 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.549          ops/ms
ClientSimple.existUser                       thrpt         13.352          ops/ms
ClientSimple.getUser                         thrpt         13.890          ops/ms
ClientSimple.listUser                        thrpt          8.888          ops/ms
ClientSimple.createUser                       avgt          2.308           ms/op
ClientSimple.existUser                        avgt          1.723           ms/op
ClientSimple.getUser                          avgt          2.115           ms/op
ClientSimple.listUser                         avgt          3.370           ms/op
ClientSimple.createUser                     sample  15675   2.037 ± 0.030   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.762           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.860           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.458           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.708           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.842           ms/op
ClientSimple.createUser:createUser·p0.999   sample         16.340           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         17.770           ms/op
ClientSimple.createUser:createUser·p1.00    sample         17.826           ms/op
ClientSimple.existUser                      sample  15254   2.100 ± 0.034   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.461           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.915           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.580           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.815           ms/op
ClientSimple.existUser:existUser·p0.99      sample          5.034           ms/op
ClientSimple.existUser:existUser·p0.999     sample         20.873           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         22.003           ms/op
ClientSimple.existUser:existUser·p1.00      sample         22.020           ms/op
ClientSimple.getUser                        sample  15903   2.011 ± 0.036   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.530           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.843           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.351           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.531           ms/op
ClientSimple.getUser:getUser·p0.99          sample          5.079           ms/op
ClientSimple.getUser:getUser·p0.999         sample         24.805           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         27.916           ms/op
ClientSimple.getUser:getUser·p1.00          sample         28.574           ms/op
ClientSimple.listUser                       sample   8899   3.597 ± 0.046   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.952           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.359           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.407           ms/op
ClientSimple.listUser:listUser·p0.95        sample          5.014           ms/op
ClientSimple.listUser:listUser·p0.99        sample          8.733           ms/op
ClientSimple.listUser:listUser·p0.999       sample         18.058           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         19.890           ms/op
ClientSimple.listUser:listUser·p1.00        sample         19.890           ms/op

Benchmark result is saved to 1724695994732.json
