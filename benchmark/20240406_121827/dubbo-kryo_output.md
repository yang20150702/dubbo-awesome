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
# Warmup Iteration   1: 1.771 ops/ms
Iteration   1: 6.927 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.927 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.552 ops/ms
Iteration   1: 9.536 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  9.536 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 5.234 ops/ms
Iteration   1: 12.946 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.946 ops/ms


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
# Warmup Iteration   1: 5.217 ops/ms
Iteration   1: 9.183 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.183 ops/ms


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
# Warmup Iteration   1: 4.206 ±(99.9%) 0.063 ms/op
Iteration   1: 2.040 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.040 ms/op


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
# Warmup Iteration   1: 3.436 ±(99.9%) 0.053 ms/op
Iteration   1: 1.853 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.853 ms/op


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
# Warmup Iteration   1: 3.229 ±(99.9%) 0.061 ms/op
Iteration   1: 1.984 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.984 ms/op


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
# Warmup Iteration   1: 5.046 ±(99.9%) 0.090 ms/op
Iteration   1: 3.403 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.403 ms/op


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
# Warmup Iteration   1: 3.843 ±(99.9%) 0.137 ms/op
Iteration   1: 2.481 ±(99.9%) 0.024 ms/op
                 createUser·p0.00:   0.822 ms/op
                 createUser·p0.50:   2.335 ms/op
                 createUser·p0.90:   3.404 ms/op
                 createUser·p0.95:   3.670 ms/op
                 createUser·p0.99:   4.350 ms/op
                 createUser·p0.999:  13.376 ms/op
                 createUser·p0.9999: 13.468 ms/op
                 createUser·p1.00:   13.468 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 12866
  mean =      2.481 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 95 
    [ 1.250,  2.500) = 7755 
    [ 2.500,  3.750) = 4534 
    [ 3.750,  5.000) = 443 
    [ 5.000,  6.250) = 3 
    [ 6.250,  7.500) = 2 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.822 ms/op
     p(50.0000) =      2.335 ms/op
     p(90.0000) =      3.404 ms/op
     p(95.0000) =      3.670 ms/op
     p(99.0000) =      4.350 ms/op
     p(99.9000) =     13.376 ms/op
     p(99.9900) =     13.468 ms/op
     p(99.9990) =     13.468 ms/op
     p(99.9999) =     13.468 ms/op
    p(100.0000) =     13.468 ms/op


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
# Warmup Iteration   1: 2.938 ±(99.9%) 0.060 ms/op
Iteration   1: 1.893 ±(99.9%) 0.032 ms/op
                 existUser·p0.00:   0.653 ms/op
                 existUser·p0.50:   1.757 ms/op
                 existUser·p0.90:   2.277 ms/op
                 existUser·p0.95:   2.429 ms/op
                 existUser·p0.99:   4.866 ms/op
                 existUser·p0.999:  24.314 ms/op
                 existUser·p0.9999: 24.924 ms/op
                 existUser·p1.00:   24.969 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16892
  mean =      1.893 ±(99.9%) 0.032 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16285 
    [ 2.500,  5.000) = 479 
    [ 5.000,  7.500) = 60 
    [ 7.500, 10.000) = 4 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.653 ms/op
     p(50.0000) =      1.757 ms/op
     p(90.0000) =      2.277 ms/op
     p(95.0000) =      2.429 ms/op
     p(99.0000) =      4.866 ms/op
     p(99.9000) =     24.314 ms/op
     p(99.9900) =     24.924 ms/op
     p(99.9990) =     24.969 ms/op
     p(99.9999) =     24.969 ms/op
    p(100.0000) =     24.969 ms/op


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
# Warmup Iteration   1: 3.550 ±(99.9%) 0.095 ms/op
Iteration   1: 2.049 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   0.741 ms/op
                 getUser·p0.50:   1.931 ms/op
                 getUser·p0.90:   2.601 ms/op
                 getUser·p0.95:   2.855 ms/op
                 getUser·p0.99:   3.808 ms/op
                 getUser·p0.999:  11.026 ms/op
                 getUser·p0.9999: 12.342 ms/op
                 getUser·p1.00:   13.418 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15613
  mean =      2.049 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 125 
    [ 1.250,  2.500) = 13363 
    [ 2.500,  3.750) = 1963 
    [ 3.750,  5.000) = 85 
    [ 5.000,  6.250) = 16 
    [ 6.250,  7.500) = 27 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 29 
    [11.250, 12.500) = 3 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.741 ms/op
     p(50.0000) =      1.931 ms/op
     p(90.0000) =      2.601 ms/op
     p(95.0000) =      2.855 ms/op
     p(99.0000) =      3.808 ms/op
     p(99.9000) =     11.026 ms/op
     p(99.9900) =     12.342 ms/op
     p(99.9990) =     13.418 ms/op
     p(99.9999) =     13.418 ms/op
    p(100.0000) =     13.418 ms/op


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
# Warmup Iteration   1: 4.604 ±(99.9%) 0.175 ms/op
Iteration   1: 3.402 ±(99.9%) 0.034 ms/op
                 listUser·p0.00:   1.049 ms/op
                 listUser·p0.50:   3.338 ms/op
                 listUser·p0.90:   4.178 ms/op
                 listUser·p0.95:   4.447 ms/op
                 listUser·p0.99:   5.662 ms/op
                 listUser·p0.999:  16.083 ms/op
                 listUser·p0.9999: 18.022 ms/op
                 listUser·p1.00:   18.022 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9381
  mean =      3.402 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 9 
    [ 1.250,  2.500) = 506 
    [ 2.500,  3.750) = 6435 
    [ 3.750,  5.000) = 2277 
    [ 5.000,  6.250) = 86 
    [ 6.250,  7.500) = 32 
    [ 7.500,  8.750) = 4 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 4 
    [15.000, 16.250) = 23 
    [16.250, 17.500) = 4 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.049 ms/op
     p(50.0000) =      3.338 ms/op
     p(90.0000) =      4.178 ms/op
     p(95.0000) =      4.447 ms/op
     p(99.0000) =      5.662 ms/op
     p(99.9000) =     16.083 ms/op
     p(99.9900) =     18.022 ms/op
     p(99.9990) =     18.022 ms/op
     p(99.9999) =     18.022 ms/op
    p(100.0000) =     18.022 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.927          ops/ms
ClientSimple.existUser                       thrpt          9.536          ops/ms
ClientSimple.getUser                         thrpt         12.946          ops/ms
ClientSimple.listUser                        thrpt          9.183          ops/ms
ClientSimple.createUser                       avgt          2.040           ms/op
ClientSimple.existUser                        avgt          1.853           ms/op
ClientSimple.getUser                          avgt          1.984           ms/op
ClientSimple.listUser                         avgt          3.403           ms/op
ClientSimple.createUser                     sample  12866   2.481 ± 0.024   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.822           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.335           ms/op
ClientSimple.createUser:createUser·p0.90    sample          3.404           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.670           ms/op
ClientSimple.createUser:createUser·p0.99    sample          4.350           ms/op
ClientSimple.createUser:createUser·p0.999   sample         13.376           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         13.468           ms/op
ClientSimple.createUser:createUser·p1.00    sample         13.468           ms/op
ClientSimple.existUser                      sample  16892   1.893 ± 0.032   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.653           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.757           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.277           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.429           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.866           ms/op
ClientSimple.existUser:existUser·p0.999     sample         24.314           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         24.924           ms/op
ClientSimple.existUser:existUser·p1.00      sample         24.969           ms/op
ClientSimple.getUser                        sample  15613   2.049 ± 0.017   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.741           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.931           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.601           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.855           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.808           ms/op
ClientSimple.getUser:getUser·p0.999         sample         11.026           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         12.342           ms/op
ClientSimple.getUser:getUser·p1.00          sample         13.418           ms/op
ClientSimple.listUser                       sample   9381   3.402 ± 0.034   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.049           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.338           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.178           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.447           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.662           ms/op
ClientSimple.listUser:listUser·p0.999       sample         16.083           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         18.022           ms/op
ClientSimple.listUser:listUser·p1.00        sample         18.022           ms/op

Benchmark result is saved to 1712405643606.json
