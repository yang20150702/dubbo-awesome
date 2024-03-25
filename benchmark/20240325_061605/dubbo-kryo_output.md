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
# Warmup Iteration   1: 1.543 ops/ms
Iteration   1: 6.965 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.965 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:19
# Fork: 1 of 1
# Warmup Iteration   1: 6.313 ops/ms
Iteration   1: 12.897 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.897 ops/ms


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
# Warmup Iteration   1: 5.169 ops/ms
Iteration   1: 12.441 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.441 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 5.036 ops/ms
Iteration   1: 8.542 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.542 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:57
# Fork: 1 of 1
# Warmup Iteration   1: 4.452 ±(99.9%) 0.089 ms/op
Iteration   1: 2.316 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.316 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:50
# Fork: 1 of 1
# Warmup Iteration   1: 3.362 ±(99.9%) 0.058 ms/op
Iteration   1: 1.969 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.969 ms/op


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
# Warmup Iteration   1: 3.420 ±(99.9%) 0.078 ms/op
Iteration   1: 2.144 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.144 ms/op


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
# Warmup Iteration   1: 4.880 ±(99.9%) 0.095 ms/op
Iteration   1: 3.590 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.590 ms/op


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
# Warmup Iteration   1: 3.866 ±(99.9%) 0.120 ms/op
Iteration   1: 2.111 ±(99.9%) 0.030 ms/op
                 createUser·p0.00:   0.626 ms/op
                 createUser·p0.50:   1.985 ms/op
                 createUser·p0.90:   2.445 ms/op
                 createUser·p0.95:   2.822 ms/op
                 createUser·p0.99:   5.513 ms/op
                 createUser·p0.999:  21.492 ms/op
                 createUser·p0.9999: 22.691 ms/op
                 createUser·p1.00:   22.741 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15118
  mean =      2.111 ±(99.9%) 0.030 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13873 
    [ 2.500,  5.000) = 1053 
    [ 5.000,  7.500) = 118 
    [ 7.500, 10.000) = 33 
    [10.000, 12.500) = 9 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.626 ms/op
     p(50.0000) =      1.985 ms/op
     p(90.0000) =      2.445 ms/op
     p(95.0000) =      2.822 ms/op
     p(99.0000) =      5.513 ms/op
     p(99.9000) =     21.492 ms/op
     p(99.9900) =     22.691 ms/op
     p(99.9990) =     22.741 ms/op
     p(99.9999) =     22.741 ms/op
    p(100.0000) =     22.741 ms/op


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
# Warmup Iteration   1: 3.000 ±(99.9%) 0.070 ms/op
Iteration   1: 2.101 ±(99.9%) 0.026 ms/op
                 existUser·p0.00:   0.628 ms/op
                 existUser·p0.50:   2.042 ms/op
                 existUser·p0.90:   2.753 ms/op
                 existUser·p0.95:   3.002 ms/op
                 existUser·p0.99:   4.923 ms/op
                 existUser·p0.999:  14.295 ms/op
                 existUser·p0.9999: 14.736 ms/op
                 existUser·p1.00:   14.762 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15369
  mean =      2.101 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1352 
    [ 1.250,  2.500) = 10588 
    [ 2.500,  3.750) = 3072 
    [ 3.750,  5.000) = 220 
    [ 5.000,  6.250) = 31 
    [ 6.250,  7.500) = 38 
    [ 7.500,  8.750) = 4 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 31 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.628 ms/op
     p(50.0000) =      2.042 ms/op
     p(90.0000) =      2.753 ms/op
     p(95.0000) =      3.002 ms/op
     p(99.0000) =      4.923 ms/op
     p(99.9000) =     14.295 ms/op
     p(99.9900) =     14.736 ms/op
     p(99.9990) =     14.762 ms/op
     p(99.9999) =     14.762 ms/op
    p(100.0000) =     14.762 ms/op


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
# Warmup Iteration   1: 3.224 ±(99.9%) 0.088 ms/op
Iteration   1: 1.899 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   0.502 ms/op
                 getUser·p0.50:   1.769 ms/op
                 getUser·p0.90:   2.445 ms/op
                 getUser·p0.95:   2.753 ms/op
                 getUser·p0.99:   3.410 ms/op
                 getUser·p0.999:  15.368 ms/op
                 getUser·p0.9999: 16.405 ms/op
                 getUser·p1.00:   16.663 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 17139
  mean =      1.899 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 255 
    [ 1.250,  2.500) = 15406 
    [ 2.500,  3.750) = 1367 
    [ 3.750,  5.000) = 41 
    [ 5.000,  6.250) = 34 
    [ 6.250,  7.500) = 4 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 29 
    [16.250, 17.500) = 3 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.502 ms/op
     p(50.0000) =      1.769 ms/op
     p(90.0000) =      2.445 ms/op
     p(95.0000) =      2.753 ms/op
     p(99.0000) =      3.410 ms/op
     p(99.9000) =     15.368 ms/op
     p(99.9900) =     16.405 ms/op
     p(99.9990) =     16.663 ms/op
     p(99.9999) =     16.663 ms/op
    p(100.0000) =     16.663 ms/op


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
# Warmup Iteration   1: 4.627 ±(99.9%) 0.128 ms/op
Iteration   1: 3.345 ±(99.9%) 0.045 ms/op
                 listUser·p0.00:   1.023 ms/op
                 listUser·p0.50:   3.129 ms/op
                 listUser·p0.90:   4.157 ms/op
                 listUser·p0.95:   4.473 ms/op
                 listUser·p0.99:   7.188 ms/op
                 listUser·p0.999:  21.955 ms/op
                 listUser·p0.9999: 22.118 ms/op
                 listUser·p1.00:   22.118 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9559
  mean =      3.345 ±(99.9%) 0.045 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1417 
    [ 2.500,  5.000) = 7930 
    [ 5.000,  7.500) = 130 
    [ 7.500, 10.000) = 49 
    [10.000, 12.500) = 1 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.023 ms/op
     p(50.0000) =      3.129 ms/op
     p(90.0000) =      4.157 ms/op
     p(95.0000) =      4.473 ms/op
     p(99.0000) =      7.188 ms/op
     p(99.9000) =     21.955 ms/op
     p(99.9900) =     22.118 ms/op
     p(99.9990) =     22.118 ms/op
     p(99.9999) =     22.118 ms/op
    p(100.0000) =     22.118 ms/op


# Run complete. Total time: 00:01:26

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.965          ops/ms
ClientSimple.existUser                       thrpt         12.897          ops/ms
ClientSimple.getUser                         thrpt         12.441          ops/ms
ClientSimple.listUser                        thrpt          8.542          ops/ms
ClientSimple.createUser                       avgt          2.316           ms/op
ClientSimple.existUser                        avgt          1.969           ms/op
ClientSimple.getUser                          avgt          2.144           ms/op
ClientSimple.listUser                         avgt          3.590           ms/op
ClientSimple.createUser                     sample  15118   2.111 ± 0.030   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.626           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.985           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.445           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.822           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.513           ms/op
ClientSimple.createUser:createUser·p0.999   sample         21.492           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         22.691           ms/op
ClientSimple.createUser:createUser·p1.00    sample         22.741           ms/op
ClientSimple.existUser                      sample  15369   2.101 ± 0.026   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.628           ms/op
ClientSimple.existUser:existUser·p0.50      sample          2.042           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.753           ms/op
ClientSimple.existUser:existUser·p0.95      sample          3.002           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.923           ms/op
ClientSimple.existUser:existUser·p0.999     sample         14.295           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         14.736           ms/op
ClientSimple.existUser:existUser·p1.00      sample         14.762           ms/op
ClientSimple.getUser                        sample  17139   1.899 ± 0.019   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.502           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.769           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.445           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.753           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.410           ms/op
ClientSimple.getUser:getUser·p0.999         sample         15.368           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         16.405           ms/op
ClientSimple.getUser:getUser·p1.00          sample         16.663           ms/op
ClientSimple.listUser                       sample   9559   3.345 ± 0.045   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.023           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.129           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.157           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.473           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.188           ms/op
ClientSimple.listUser:listUser·p0.999       sample         21.955           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         22.118           ms/op
ClientSimple.listUser:listUser·p1.00        sample         22.118           ms/op

Benchmark result is saved to 1711347128725.json
