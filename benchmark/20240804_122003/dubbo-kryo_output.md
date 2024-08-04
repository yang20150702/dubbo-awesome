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
# Warmup Iteration   1: 1.847 ops/ms
Iteration   1: 7.104 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.104 ops/ms


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
# Warmup Iteration   1: 6.745 ops/ms
Iteration   1: 13.276 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.276 ops/ms


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
# Warmup Iteration   1: 5.753 ops/ms
Iteration   1: 9.308 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  9.308 ops/ms


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
# Warmup Iteration   1: 5.574 ops/ms
Iteration   1: 9.161 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.161 ops/ms


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
# Warmup Iteration   1: 4.155 ±(99.9%) 0.073 ms/op
Iteration   1: 2.290 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.290 ms/op


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
# Warmup Iteration   1: 3.150 ±(99.9%) 0.057 ms/op
Iteration   1: 1.897 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.897 ms/op


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
# Warmup Iteration   1: 3.220 ±(99.9%) 0.051 ms/op
Iteration   1: 1.987 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.987 ms/op


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
# Warmup Iteration   1: 4.131 ±(99.9%) 0.093 ms/op
Iteration   1: 3.013 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.013 ms/op


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
# Warmup Iteration   1: 3.851 ±(99.9%) 0.111 ms/op
Iteration   1: 2.305 ±(99.9%) 0.030 ms/op
                 createUser·p0.00:   0.556 ms/op
                 createUser·p0.50:   2.220 ms/op
                 createUser·p0.90:   2.662 ms/op
                 createUser·p0.95:   2.884 ms/op
                 createUser·p0.99:   5.185 ms/op
                 createUser·p0.999:  17.406 ms/op
                 createUser·p0.9999: 19.891 ms/op
                 createUser·p1.00:   20.185 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13900
  mean =      2.305 ±(99.9%) 0.030 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10800 
    [ 2.500,  5.000) = 2915 
    [ 5.000,  7.500) = 86 
    [ 7.500, 10.000) = 35 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 20 
    [17.500, 20.000) = 11 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.556 ms/op
     p(50.0000) =      2.220 ms/op
     p(90.0000) =      2.662 ms/op
     p(95.0000) =      2.884 ms/op
     p(99.0000) =      5.185 ms/op
     p(99.9000) =     17.406 ms/op
     p(99.9900) =     19.891 ms/op
     p(99.9990) =     20.185 ms/op
     p(99.9999) =     20.185 ms/op
    p(100.0000) =     20.185 ms/op


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
# Warmup Iteration   1: 3.256 ±(99.9%) 0.094 ms/op
Iteration   1: 1.889 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   0.650 ms/op
                 existUser·p0.50:   1.798 ms/op
                 existUser·p0.90:   2.434 ms/op
                 existUser·p0.95:   2.687 ms/op
                 existUser·p0.99:   3.518 ms/op
                 existUser·p0.999:  12.501 ms/op
                 existUser·p0.9999: 12.965 ms/op
                 existUser·p1.00:   12.976 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16927
  mean =      1.889 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 696 
    [ 1.250,  2.500) = 14815 
    [ 2.500,  3.750) = 1268 
    [ 3.750,  5.000) = 93 
    [ 5.000,  6.250) = 22 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 15 
    [12.500, 13.750) = 17 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.650 ms/op
     p(50.0000) =      1.798 ms/op
     p(90.0000) =      2.434 ms/op
     p(95.0000) =      2.687 ms/op
     p(99.0000) =      3.518 ms/op
     p(99.9000) =     12.501 ms/op
     p(99.9900) =     12.965 ms/op
     p(99.9990) =     12.976 ms/op
     p(99.9999) =     12.976 ms/op
    p(100.0000) =     12.976 ms/op


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
# Warmup Iteration   1: 3.347 ±(99.9%) 0.089 ms/op
Iteration   1: 2.077 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   0.492 ms/op
                 getUser·p0.50:   1.964 ms/op
                 getUser·p0.90:   2.578 ms/op
                 getUser·p0.95:   2.757 ms/op
                 getUser·p0.99:   3.482 ms/op
                 getUser·p0.999:  13.258 ms/op
                 getUser·p0.9999: 15.427 ms/op
                 getUser·p1.00:   15.516 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15386
  mean =      2.077 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 156 
    [ 1.250,  2.500) = 13112 
    [ 2.500,  3.750) = 1987 
    [ 3.750,  5.000) = 2 
    [ 5.000,  6.250) = 87 
    [ 6.250,  7.500) = 10 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 5 
    [12.500, 13.750) = 20 
    [13.750, 15.000) = 5 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.492 ms/op
     p(50.0000) =      1.964 ms/op
     p(90.0000) =      2.578 ms/op
     p(95.0000) =      2.757 ms/op
     p(99.0000) =      3.482 ms/op
     p(99.9000) =     13.258 ms/op
     p(99.9900) =     15.427 ms/op
     p(99.9990) =     15.516 ms/op
     p(99.9999) =     15.516 ms/op
    p(100.0000) =     15.516 ms/op


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
# Warmup Iteration   1: 4.794 ±(99.9%) 0.158 ms/op
Iteration   1: 3.916 ±(99.9%) 0.068 ms/op
                 listUser·p0.00:   1.130 ms/op
                 listUser·p0.50:   3.826 ms/op
                 listUser·p0.90:   4.530 ms/op
                 listUser·p0.95:   5.139 ms/op
                 listUser·p0.99:   7.886 ms/op
                 listUser·p0.999:  29.157 ms/op
                 listUser·p0.9999: 30.769 ms/op
                 listUser·p1.00:   30.769 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8212
  mean =      3.916 ±(99.9%) 0.068 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 404 
    [ 2.500,  5.000) = 7310 
    [ 5.000,  7.500) = 359 
    [ 7.500, 10.000) = 69 
    [10.000, 12.500) = 1 
    [12.500, 15.000) = 3 
    [15.000, 17.500) = 36 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 3 
    [27.500, 30.000) = 19 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.130 ms/op
     p(50.0000) =      3.826 ms/op
     p(90.0000) =      4.530 ms/op
     p(95.0000) =      5.139 ms/op
     p(99.0000) =      7.886 ms/op
     p(99.9000) =     29.157 ms/op
     p(99.9900) =     30.769 ms/op
     p(99.9990) =     30.769 ms/op
     p(99.9999) =     30.769 ms/op
    p(100.0000) =     30.769 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.104          ops/ms
ClientSimple.existUser                       thrpt         13.276          ops/ms
ClientSimple.getUser                         thrpt          9.308          ops/ms
ClientSimple.listUser                        thrpt          9.161          ops/ms
ClientSimple.createUser                       avgt          2.290           ms/op
ClientSimple.existUser                        avgt          1.897           ms/op
ClientSimple.getUser                          avgt          1.987           ms/op
ClientSimple.listUser                         avgt          3.013           ms/op
ClientSimple.createUser                     sample  13900   2.305 ± 0.030   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.556           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.220           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.662           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.884           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.185           ms/op
ClientSimple.createUser:createUser·p0.999   sample         17.406           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         19.891           ms/op
ClientSimple.createUser:createUser·p1.00    sample         20.185           ms/op
ClientSimple.existUser                      sample  16927   1.889 ± 0.017   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.650           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.798           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.434           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.687           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.518           ms/op
ClientSimple.existUser:existUser·p0.999     sample         12.501           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         12.965           ms/op
ClientSimple.existUser:existUser·p1.00      sample         12.976           ms/op
ClientSimple.getUser                        sample  15386   2.077 ± 0.019   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.492           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.964           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.578           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.757           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.482           ms/op
ClientSimple.getUser:getUser·p0.999         sample         13.258           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         15.427           ms/op
ClientSimple.getUser:getUser·p1.00          sample         15.516           ms/op
ClientSimple.listUser                       sample   8212   3.916 ± 0.068   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.130           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.826           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.530           ms/op
ClientSimple.listUser:listUser·p0.95        sample          5.139           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.886           ms/op
ClientSimple.listUser:listUser·p0.999       sample         29.157           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         30.769           ms/op
ClientSimple.listUser:listUser·p1.00        sample         30.769           ms/op

Benchmark result is saved to 1722773735960.json
