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
# Warmup Iteration   1: 1.431 ops/ms
Iteration   1: 6.481 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.481 ops/ms


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
# Warmup Iteration   1: 6.165 ops/ms
Iteration   1: 11.681 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.681 ops/ms


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
# Warmup Iteration   1: 5.141 ops/ms
Iteration   1: 12.455 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.455 ops/ms


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
# Warmup Iteration   1: 4.255 ops/ms
Iteration   1: 7.404 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  7.404 ops/ms


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
# Warmup Iteration   1: 4.252 ±(99.9%) 0.076 ms/op
Iteration   1: 2.296 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.296 ms/op


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
# Warmup Iteration   1: 3.370 ±(99.9%) 0.056 ms/op
Iteration   1: 2.022 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.022 ms/op


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
# Warmup Iteration   1: 3.350 ±(99.9%) 0.057 ms/op
Iteration   1: 1.973 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.973 ms/op


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
# Warmup Iteration   1: 5.293 ±(99.9%) 0.100 ms/op
Iteration   1: 3.426 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.426 ms/op


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
# Warmup Iteration   1: 3.710 ±(99.9%) 0.088 ms/op
Iteration   1: 2.597 ±(99.9%) 0.041 ms/op
                 createUser·p0.00:   0.451 ms/op
                 createUser·p0.50:   2.425 ms/op
                 createUser·p0.90:   3.101 ms/op
                 createUser·p0.95:   3.654 ms/op
                 createUser·p0.99:   10.049 ms/op
                 createUser·p0.999:  15.761 ms/op
                 createUser·p0.9999: 19.615 ms/op
                 createUser·p1.00:   19.661 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 12316
  mean =      2.597 ±(99.9%) 0.041 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 247 
    [ 1.250,  2.500) = 6839 
    [ 2.500,  3.750) = 4644 
    [ 3.750,  5.000) = 225 
    [ 5.000,  6.250) = 73 
    [ 6.250,  7.500) = 60 
    [ 7.500,  8.750) = 81 
    [ 8.750, 10.000) = 24 
    [10.000, 11.250) = 11 
    [11.250, 12.500) = 41 
    [12.500, 13.750) = 31 
    [13.750, 15.000) = 7 
    [15.000, 16.250) = 31 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.451 ms/op
     p(50.0000) =      2.425 ms/op
     p(90.0000) =      3.101 ms/op
     p(95.0000) =      3.654 ms/op
     p(99.0000) =     10.049 ms/op
     p(99.9000) =     15.761 ms/op
     p(99.9900) =     19.615 ms/op
     p(99.9990) =     19.661 ms/op
     p(99.9999) =     19.661 ms/op
    p(100.0000) =     19.661 ms/op


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
# Warmup Iteration   1: 3.009 ±(99.9%) 0.075 ms/op
Iteration   1: 1.874 ±(99.9%) 0.022 ms/op
                 existUser·p0.00:   0.509 ms/op
                 existUser·p0.50:   1.735 ms/op
                 existUser·p0.90:   2.404 ms/op
                 existUser·p0.95:   2.638 ms/op
                 existUser·p0.99:   4.383 ms/op
                 existUser·p0.999:  15.138 ms/op
                 existUser·p0.9999: 15.287 ms/op
                 existUser·p1.00:   15.368 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17059
  mean =      1.874 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 532 
    [ 1.250,  2.500) = 15264 
    [ 2.500,  3.750) = 1029 
    [ 3.750,  5.000) = 92 
    [ 5.000,  6.250) = 71 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 3 
    [10.000, 11.250) = 35 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 3 
    [15.000, 16.250) = 29 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.509 ms/op
     p(50.0000) =      1.735 ms/op
     p(90.0000) =      2.404 ms/op
     p(95.0000) =      2.638 ms/op
     p(99.0000) =      4.383 ms/op
     p(99.9000) =     15.138 ms/op
     p(99.9900) =     15.287 ms/op
     p(99.9990) =     15.368 ms/op
     p(99.9999) =     15.368 ms/op
    p(100.0000) =     15.368 ms/op


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
# Warmup Iteration   1: 3.590 ±(99.9%) 0.113 ms/op
Iteration   1: 2.305 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   0.253 ms/op
                 getUser·p0.50:   2.191 ms/op
                 getUser·p0.90:   2.892 ms/op
                 getUser·p0.95:   3.129 ms/op
                 getUser·p0.99:   5.403 ms/op
                 getUser·p0.999:  13.846 ms/op
                 getUser·p0.9999: 14.352 ms/op
                 getUser·p1.00:   14.352 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 13942
  mean =      2.305 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 207 
    [ 1.250,  2.500) = 9327 
    [ 2.500,  3.750) = 4147 
    [ 3.750,  5.000) = 110 
    [ 5.000,  6.250) = 84 
    [ 6.250,  7.500) = 32 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 13 
    [13.750, 15.000) = 22 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.253 ms/op
     p(50.0000) =      2.191 ms/op
     p(90.0000) =      2.892 ms/op
     p(95.0000) =      3.129 ms/op
     p(99.0000) =      5.403 ms/op
     p(99.9000) =     13.846 ms/op
     p(99.9900) =     14.352 ms/op
     p(99.9990) =     14.352 ms/op
     p(99.9999) =     14.352 ms/op
    p(100.0000) =     14.352 ms/op


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
# Warmup Iteration   1: 4.665 ±(99.9%) 0.136 ms/op
Iteration   1: 4.201 ±(99.9%) 0.093 ms/op
                 listUser·p0.00:   0.770 ms/op
                 listUser·p0.50:   3.940 ms/op
                 listUser·p0.90:   4.923 ms/op
                 listUser·p0.95:   5.530 ms/op
                 listUser·p0.99:   14.004 ms/op
                 listUser·p0.999:  35.219 ms/op
                 listUser·p0.9999: 35.455 ms/op
                 listUser·p1.00:   35.455 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 7606
  mean =      4.201 ±(99.9%) 0.093 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 217 
    [ 2.500,  5.000) = 6701 
    [ 5.000,  7.500) = 554 
    [ 7.500, 10.000) = 6 
    [10.000, 12.500) = 25 
    [12.500, 15.000) = 39 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 22 
    [35.000, 37.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      0.770 ms/op
     p(50.0000) =      3.940 ms/op
     p(90.0000) =      4.923 ms/op
     p(95.0000) =      5.530 ms/op
     p(99.0000) =     14.004 ms/op
     p(99.9000) =     35.219 ms/op
     p(99.9900) =     35.455 ms/op
     p(99.9990) =     35.455 ms/op
     p(99.9999) =     35.455 ms/op
    p(100.0000) =     35.455 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.481          ops/ms
ClientSimple.existUser                       thrpt         11.681          ops/ms
ClientSimple.getUser                         thrpt         12.455          ops/ms
ClientSimple.listUser                        thrpt          7.404          ops/ms
ClientSimple.createUser                       avgt          2.296           ms/op
ClientSimple.existUser                        avgt          2.022           ms/op
ClientSimple.getUser                          avgt          1.973           ms/op
ClientSimple.listUser                         avgt          3.426           ms/op
ClientSimple.createUser                     sample  12316   2.597 ± 0.041   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.451           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.425           ms/op
ClientSimple.createUser:createUser·p0.90    sample          3.101           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.654           ms/op
ClientSimple.createUser:createUser·p0.99    sample         10.049           ms/op
ClientSimple.createUser:createUser·p0.999   sample         15.761           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         19.615           ms/op
ClientSimple.createUser:createUser·p1.00    sample         19.661           ms/op
ClientSimple.existUser                      sample  17059   1.874 ± 0.022   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.509           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.735           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.404           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.638           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.383           ms/op
ClientSimple.existUser:existUser·p0.999     sample         15.138           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         15.287           ms/op
ClientSimple.existUser:existUser·p1.00      sample         15.368           ms/op
ClientSimple.getUser                        sample  13942   2.305 ± 0.024   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.253           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.191           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.892           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.129           ms/op
ClientSimple.getUser:getUser·p0.99          sample          5.403           ms/op
ClientSimple.getUser:getUser·p0.999         sample         13.846           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         14.352           ms/op
ClientSimple.getUser:getUser·p1.00          sample         14.352           ms/op
ClientSimple.listUser                       sample   7606   4.201 ± 0.093   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.770           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.940           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.923           ms/op
ClientSimple.listUser:listUser·p0.95        sample          5.530           ms/op
ClientSimple.listUser:listUser·p0.99        sample         14.004           ms/op
ClientSimple.listUser:listUser·p0.999       sample         35.219           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         35.455           ms/op
ClientSimple.listUser:listUser·p1.00        sample         35.455           ms/op

Benchmark result is saved to 1721218635265.json
