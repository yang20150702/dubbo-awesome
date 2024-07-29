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
# Warmup Iteration   1: 1.570 ops/ms
Iteration   1: 6.395 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.395 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:19
# Fork: 1 of 1
# Warmup Iteration   1: 6.032 ops/ms
Iteration   1: 11.344 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.344 ops/ms


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
# Warmup Iteration   1: 6.096 ops/ms
Iteration   1: 13.714 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.714 ops/ms


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
# Warmup Iteration   1: 4.453 ops/ms
Iteration   1: 9.013 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.013 ops/ms


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
# Warmup Iteration   1: 4.125 ±(99.9%) 0.077 ms/op
Iteration   1: 2.380 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.380 ms/op


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
# Warmup Iteration   1: 3.289 ±(99.9%) 0.069 ms/op
Iteration   1: 2.080 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.080 ms/op


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
# Warmup Iteration   1: 3.528 ±(99.9%) 0.077 ms/op
Iteration   1: 2.029 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.029 ms/op


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
# Warmup Iteration   1: 4.126 ±(99.9%) 0.084 ms/op
Iteration   1: 3.505 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.505 ms/op


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
# Warmup Iteration   1: 3.722 ±(99.9%) 0.095 ms/op
Iteration   1: 2.408 ±(99.9%) 0.045 ms/op
                 createUser·p0.00:   0.679 ms/op
                 createUser·p0.50:   2.175 ms/op
                 createUser·p0.90:   2.822 ms/op
                 createUser·p0.95:   3.310 ms/op
                 createUser·p0.99:   12.993 ms/op
                 createUser·p0.999:  16.592 ms/op
                 createUser·p0.9999: 19.817 ms/op
                 createUser·p1.00:   19.988 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13277
  mean =      2.408 ±(99.9%) 0.045 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 387 
    [ 1.250,  2.500) = 10197 
    [ 2.500,  3.750) = 2152 
    [ 3.750,  5.000) = 160 
    [ 5.000,  6.250) = 147 
    [ 6.250,  7.500) = 15 
    [ 7.500,  8.750) = 17 
    [ 8.750, 10.000) = 14 
    [10.000, 11.250) = 7 
    [11.250, 12.500) = 28 
    [12.500, 13.750) = 74 
    [13.750, 15.000) = 8 
    [15.000, 16.250) = 49 
    [16.250, 17.500) = 16 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.679 ms/op
     p(50.0000) =      2.175 ms/op
     p(90.0000) =      2.822 ms/op
     p(95.0000) =      3.310 ms/op
     p(99.0000) =     12.993 ms/op
     p(99.9000) =     16.592 ms/op
     p(99.9900) =     19.817 ms/op
     p(99.9990) =     19.988 ms/op
     p(99.9999) =     19.988 ms/op
    p(100.0000) =     19.988 ms/op


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
# Warmup Iteration   1: 3.150 ±(99.9%) 0.095 ms/op
Iteration   1: 1.977 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   0.224 ms/op
                 existUser·p0.50:   1.917 ms/op
                 existUser·p0.90:   2.490 ms/op
                 existUser·p0.95:   2.650 ms/op
                 existUser·p0.99:   3.232 ms/op
                 existUser·p0.999:  11.021 ms/op
                 existUser·p0.9999: 12.451 ms/op
                 existUser·p1.00:   12.616 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16268
  mean =      1.977 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 277 
    [ 1.250,  2.500) = 14447 
    [ 2.500,  3.750) = 1471 
    [ 3.750,  5.000) = 27 
    [ 5.000,  6.250) = 13 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 18 
    [11.250, 12.500) = 13 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.224 ms/op
     p(50.0000) =      1.917 ms/op
     p(90.0000) =      2.490 ms/op
     p(95.0000) =      2.650 ms/op
     p(99.0000) =      3.232 ms/op
     p(99.9000) =     11.021 ms/op
     p(99.9900) =     12.451 ms/op
     p(99.9990) =     12.616 ms/op
     p(99.9999) =     12.616 ms/op
    p(100.0000) =     12.616 ms/op


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
# Warmup Iteration   1: 3.537 ±(99.9%) 0.122 ms/op
Iteration   1: 1.945 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   0.471 ms/op
                 getUser·p0.50:   1.888 ms/op
                 getUser·p0.90:   2.339 ms/op
                 getUser·p0.95:   2.478 ms/op
                 getUser·p0.99:   3.086 ms/op
                 getUser·p0.999:  13.386 ms/op
                 getUser·p0.9999: 14.178 ms/op
                 getUser·p1.00:   14.189 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16458
  mean =      1.945 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 159 
    [ 1.250,  2.500) = 15562 
    [ 2.500,  3.750) = 654 
    [ 3.750,  5.000) = 6 
    [ 5.000,  6.250) = 10 
    [ 6.250,  7.500) = 2 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 32 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 19 
    [13.750, 15.000) = 13 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.471 ms/op
     p(50.0000) =      1.888 ms/op
     p(90.0000) =      2.339 ms/op
     p(95.0000) =      2.478 ms/op
     p(99.0000) =      3.086 ms/op
     p(99.9000) =     13.386 ms/op
     p(99.9900) =     14.178 ms/op
     p(99.9990) =     14.189 ms/op
     p(99.9999) =     14.189 ms/op
    p(100.0000) =     14.189 ms/op


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
# Warmup Iteration   1: 5.037 ±(99.9%) 0.345 ms/op
Iteration   1: 3.583 ±(99.9%) 0.073 ms/op
                 listUser·p0.00:   1.130 ms/op
                 listUser·p0.50:   3.363 ms/op
                 listUser·p0.90:   4.391 ms/op
                 listUser·p0.95:   5.005 ms/op
                 listUser·p0.99:   8.892 ms/op
                 listUser·p0.999:  30.835 ms/op
                 listUser·p0.9999: 31.654 ms/op
                 listUser·p1.00:   31.654 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8929
  mean =      3.583 ±(99.9%) 0.073 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 926 
    [ 2.500,  5.000) = 7557 
    [ 5.000,  7.500) = 339 
    [ 7.500, 10.000) = 43 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 4 
    [30.000, 32.500) = 28 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.130 ms/op
     p(50.0000) =      3.363 ms/op
     p(90.0000) =      4.391 ms/op
     p(95.0000) =      5.005 ms/op
     p(99.0000) =      8.892 ms/op
     p(99.9000) =     30.835 ms/op
     p(99.9900) =     31.654 ms/op
     p(99.9990) =     31.654 ms/op
     p(99.9999) =     31.654 ms/op
    p(100.0000) =     31.654 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.395          ops/ms
ClientSimple.existUser                       thrpt         11.344          ops/ms
ClientSimple.getUser                         thrpt         13.714          ops/ms
ClientSimple.listUser                        thrpt          9.013          ops/ms
ClientSimple.createUser                       avgt          2.380           ms/op
ClientSimple.existUser                        avgt          2.080           ms/op
ClientSimple.getUser                          avgt          2.029           ms/op
ClientSimple.listUser                         avgt          3.505           ms/op
ClientSimple.createUser                     sample  13277   2.408 ± 0.045   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.679           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.175           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.822           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.310           ms/op
ClientSimple.createUser:createUser·p0.99    sample         12.993           ms/op
ClientSimple.createUser:createUser·p0.999   sample         16.592           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         19.817           ms/op
ClientSimple.createUser:createUser·p1.00    sample         19.988           ms/op
ClientSimple.existUser                      sample  16268   1.977 ± 0.016   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.224           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.917           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.490           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.650           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.232           ms/op
ClientSimple.existUser:existUser·p0.999     sample         11.021           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         12.451           ms/op
ClientSimple.existUser:existUser·p1.00      sample         12.616           ms/op
ClientSimple.getUser                        sample  16458   1.945 ± 0.018   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.471           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.888           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.339           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.478           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.086           ms/op
ClientSimple.getUser:getUser·p0.999         sample         13.386           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         14.178           ms/op
ClientSimple.getUser:getUser·p1.00          sample         14.189           ms/op
ClientSimple.listUser                       sample   8929   3.583 ± 0.073   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.130           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.363           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.391           ms/op
ClientSimple.listUser:listUser·p0.95        sample          5.005           ms/op
ClientSimple.listUser:listUser·p0.99        sample          8.892           ms/op
ClientSimple.listUser:listUser·p0.999       sample         30.835           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         31.654           ms/op
ClientSimple.listUser:listUser·p1.00        sample         31.654           ms/op

Benchmark result is saved to 1722213846592.json
