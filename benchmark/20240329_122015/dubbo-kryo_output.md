# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 1.921 ops/ms
Iteration   1: 7.412 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.412 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 6.420 ops/ms
Iteration   1: 13.284 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.284 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 16.67% complete, ETA 00:01:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.895 ops/ms
Iteration   1: 12.642 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.642 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 5.437 ops/ms
Iteration   1: 8.246 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.246 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.649 ±(99.9%) 0.107 ms/op
Iteration   1: 2.151 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.151 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.447 ±(99.9%) 0.085 ms/op
Iteration   1: 1.726 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.726 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 3.233 ±(99.9%) 0.057 ms/op
Iteration   1: 2.063 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.063 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 4.529 ±(99.9%) 0.072 ms/op
Iteration   1: 3.342 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.342 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.525 ±(99.9%) 0.118 ms/op
Iteration   1: 2.146 ±(99.9%) 0.035 ms/op
                 createUser·p0.00:   0.542 ms/op
                 createUser·p0.50:   1.886 ms/op
                 createUser·p0.90:   2.642 ms/op
                 createUser·p0.95:   3.006 ms/op
                 createUser·p0.99:   8.618 ms/op
                 createUser·p0.999:  18.452 ms/op
                 createUser·p0.9999: 19.809 ms/op
                 createUser·p1.00:   19.857 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14899
  mean =      2.146 ±(99.9%) 0.035 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 121 
    [ 1.250,  2.500) = 12682 
    [ 2.500,  3.750) = 1690 
    [ 3.750,  5.000) = 143 
    [ 5.000,  6.250) = 7 
    [ 6.250,  7.500) = 61 
    [ 7.500,  8.750) = 54 
    [ 8.750, 10.000) = 40 
    [10.000, 11.250) = 5 
    [11.250, 12.500) = 14 
    [12.500, 13.750) = 47 
    [13.750, 15.000) = 3 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 24 

  Percentiles, ms/op:
      p(0.0000) =      0.542 ms/op
     p(50.0000) =      1.886 ms/op
     p(90.0000) =      2.642 ms/op
     p(95.0000) =      3.006 ms/op
     p(99.0000) =      8.618 ms/op
     p(99.9000) =     18.452 ms/op
     p(99.9900) =     19.809 ms/op
     p(99.9990) =     19.857 ms/op
     p(99.9999) =     19.857 ms/op
    p(100.0000) =     19.857 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 3.081 ±(99.9%) 0.095 ms/op
Iteration   1: 2.052 ±(99.9%) 0.022 ms/op
                 existUser·p0.00:   0.752 ms/op
                 existUser·p0.50:   1.948 ms/op
                 existUser·p0.90:   2.486 ms/op
                 existUser·p0.95:   2.621 ms/op
                 existUser·p0.99:   4.062 ms/op
                 existUser·p0.999:  14.989 ms/op
                 existUser·p0.9999: 15.838 ms/op
                 existUser·p1.00:   15.892 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15579
  mean =      2.052 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 193 
    [ 1.250,  2.500) = 13949 
    [ 2.500,  3.750) = 1224 
    [ 3.750,  5.000) = 110 
    [ 5.000,  6.250) = 25 
    [ 6.250,  7.500) = 14 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 32 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 17 
    [15.000, 16.250) = 15 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.752 ms/op
     p(50.0000) =      1.948 ms/op
     p(90.0000) =      2.486 ms/op
     p(95.0000) =      2.621 ms/op
     p(99.0000) =      4.062 ms/op
     p(99.9000) =     14.989 ms/op
     p(99.9900) =     15.838 ms/op
     p(99.9990) =     15.892 ms/op
     p(99.9999) =     15.892 ms/op
    p(100.0000) =     15.892 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.102 ±(99.9%) 0.087 ms/op
Iteration   1: 2.016 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   0.605 ms/op
                 getUser·p0.50:   1.915 ms/op
                 getUser·p0.90:   2.404 ms/op
                 getUser·p0.95:   2.561 ms/op
                 getUser·p0.99:   3.109 ms/op
                 getUser·p0.999:  14.616 ms/op
                 getUser·p0.9999: 17.512 ms/op
                 getUser·p1.00:   17.531 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15893
  mean =      2.016 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 84 
    [ 1.250,  2.500) = 14734 
    [ 2.500,  3.750) = 977 
    [ 3.750,  5.000) = 40 
    [ 5.000,  6.250) = 26 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 29 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 2 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.605 ms/op
     p(50.0000) =      1.915 ms/op
     p(90.0000) =      2.404 ms/op
     p(95.0000) =      2.561 ms/op
     p(99.0000) =      3.109 ms/op
     p(99.9000) =     14.616 ms/op
     p(99.9900) =     17.512 ms/op
     p(99.9990) =     17.531 ms/op
     p(99.9999) =     17.531 ms/op
    p(100.0000) =     17.531 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.286 ±(99.9%) 0.122 ms/op
Iteration   1: 3.337 ±(99.9%) 0.031 ms/op
                 listUser·p0.00:   1.464 ms/op
                 listUser·p0.50:   3.125 ms/op
                 listUser·p0.90:   4.129 ms/op
                 listUser·p0.95:   4.334 ms/op
                 listUser·p0.99:   5.237 ms/op
                 listUser·p0.999:  14.959 ms/op
                 listUser·p0.9999: 15.106 ms/op
                 listUser·p1.00:   15.106 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9568
  mean =      3.337 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 353 
    [ 2.500,  3.750) = 6938 
    [ 3.750,  5.000) = 2145 
    [ 5.000,  6.250) = 83 
    [ 6.250,  7.500) = 16 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 27 
    [15.000, 16.250) = 5 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.464 ms/op
     p(50.0000) =      3.125 ms/op
     p(90.0000) =      4.129 ms/op
     p(95.0000) =      4.334 ms/op
     p(99.0000) =      5.237 ms/op
     p(99.9000) =     14.959 ms/op
     p(99.9900) =     15.106 ms/op
     p(99.9990) =     15.106 ms/op
     p(99.9999) =     15.106 ms/op
    p(100.0000) =     15.106 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.412          ops/ms
ClientSimple.existUser                       thrpt         13.284          ops/ms
ClientSimple.getUser                         thrpt         12.642          ops/ms
ClientSimple.listUser                        thrpt          8.246          ops/ms
ClientSimple.createUser                       avgt          2.151           ms/op
ClientSimple.existUser                        avgt          1.726           ms/op
ClientSimple.getUser                          avgt          2.063           ms/op
ClientSimple.listUser                         avgt          3.342           ms/op
ClientSimple.createUser                     sample  14899   2.146 ± 0.035   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.542           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.886           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.642           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.006           ms/op
ClientSimple.createUser:createUser·p0.99    sample          8.618           ms/op
ClientSimple.createUser:createUser·p0.999   sample         18.452           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         19.809           ms/op
ClientSimple.createUser:createUser·p1.00    sample         19.857           ms/op
ClientSimple.existUser                      sample  15579   2.052 ± 0.022   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.752           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.948           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.486           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.621           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.062           ms/op
ClientSimple.existUser:existUser·p0.999     sample         14.989           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         15.838           ms/op
ClientSimple.existUser:existUser·p1.00      sample         15.892           ms/op
ClientSimple.getUser                        sample  15893   2.016 ± 0.018   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.605           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.915           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.404           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.561           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.109           ms/op
ClientSimple.getUser:getUser·p0.999         sample         14.616           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         17.512           ms/op
ClientSimple.getUser:getUser·p1.00          sample         17.531           ms/op
ClientSimple.listUser                       sample   9568   3.337 ± 0.031   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.464           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.125           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.129           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.334           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.237           ms/op
ClientSimple.listUser:listUser·p0.999       sample         14.959           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         15.106           ms/op
ClientSimple.listUser:listUser·p1.00        sample         15.106           ms/op

Benchmark result is saved to 1711714529495.json
