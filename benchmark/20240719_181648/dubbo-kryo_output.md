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
# Warmup Iteration   1: 1.749 ops/ms
Iteration   1: 7.050 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.050 ops/ms


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
# Warmup Iteration   1: 6.404 ops/ms
Iteration   1: 12.286 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.286 ops/ms


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
# Warmup Iteration   1: 6.100 ops/ms
Iteration   1: 14.476 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  14.476 ops/ms


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
# Warmup Iteration   1: 5.361 ops/ms
Iteration   1: 8.503 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.503 ops/ms


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
# Warmup Iteration   1: 3.865 ±(99.9%) 0.065 ms/op
Iteration   1: 2.327 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.327 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 2.927 ±(99.9%) 0.053 ms/op
Iteration   1: 1.879 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.879 ms/op


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
# Warmup Iteration   1: 3.251 ±(99.9%) 0.055 ms/op
Iteration   1: 2.046 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.046 ms/op


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
# Warmup Iteration   1: 4.517 ±(99.9%) 0.102 ms/op
Iteration   1: 3.478 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.478 ms/op


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
# Warmup Iteration   1: 3.719 ±(99.9%) 0.108 ms/op
Iteration   1: 2.089 ±(99.9%) 0.028 ms/op
                 createUser·p0.00:   0.624 ms/op
                 createUser·p0.50:   1.884 ms/op
                 createUser·p0.90:   2.576 ms/op
                 createUser·p0.95:   3.076 ms/op
                 createUser·p0.99:   4.695 ms/op
                 createUser·p0.999:  17.138 ms/op
                 createUser·p0.9999: 17.350 ms/op
                 createUser·p1.00:   17.367 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15288
  mean =      2.089 ±(99.9%) 0.028 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 66 
    [ 1.250,  2.500) = 13339 
    [ 2.500,  3.750) = 1503 
    [ 3.750,  5.000) = 236 
    [ 5.000,  6.250) = 47 
    [ 6.250,  7.500) = 7 
    [ 7.500,  8.750) = 26 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 7 
    [12.500, 13.750) = 16 
    [13.750, 15.000) = 9 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 32 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.624 ms/op
     p(50.0000) =      1.884 ms/op
     p(90.0000) =      2.576 ms/op
     p(95.0000) =      3.076 ms/op
     p(99.0000) =      4.695 ms/op
     p(99.9000) =     17.138 ms/op
     p(99.9900) =     17.350 ms/op
     p(99.9990) =     17.367 ms/op
     p(99.9999) =     17.367 ms/op
    p(100.0000) =     17.367 ms/op


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
# Warmup Iteration   1: 3.004 ±(99.9%) 0.063 ms/op
Iteration   1: 1.934 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   0.540 ms/op
                 existUser·p0.50:   1.839 ms/op
                 existUser·p0.90:   2.400 ms/op
                 existUser·p0.95:   2.735 ms/op
                 existUser·p0.99:   4.243 ms/op
                 existUser·p0.999:  11.853 ms/op
                 existUser·p0.9999: 12.252 ms/op
                 existUser·p1.00:   12.337 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16526
  mean =      1.934 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 404 
    [ 1.250,  2.500) = 14829 
    [ 2.500,  3.750) = 1038 
    [ 3.750,  5.000) = 157 
    [ 5.000,  6.250) = 47 
    [ 6.250,  7.500) = 19 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 3 
    [11.250, 12.500) = 29 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.540 ms/op
     p(50.0000) =      1.839 ms/op
     p(90.0000) =      2.400 ms/op
     p(95.0000) =      2.735 ms/op
     p(99.0000) =      4.243 ms/op
     p(99.9000) =     11.853 ms/op
     p(99.9900) =     12.252 ms/op
     p(99.9990) =     12.337 ms/op
     p(99.9999) =     12.337 ms/op
    p(100.0000) =     12.337 ms/op


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
# Warmup Iteration   1: 3.491 ±(99.9%) 0.106 ms/op
Iteration   1: 2.160 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   0.700 ms/op
                 getUser·p0.50:   1.985 ms/op
                 getUser·p0.90:   2.888 ms/op
                 getUser·p0.95:   3.178 ms/op
                 getUser·p0.99:   3.547 ms/op
                 getUser·p0.999:  15.896 ms/op
                 getUser·p0.9999: 16.115 ms/op
                 getUser·p1.00:   16.155 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14804
  mean =      2.160 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 116 
    [ 1.250,  2.500) = 11784 
    [ 2.500,  3.750) = 2833 
    [ 3.750,  5.000) = 35 
    [ 5.000,  6.250) = 3 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 32 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.700 ms/op
     p(50.0000) =      1.985 ms/op
     p(90.0000) =      2.888 ms/op
     p(95.0000) =      3.178 ms/op
     p(99.0000) =      3.547 ms/op
     p(99.9000) =     15.896 ms/op
     p(99.9900) =     16.115 ms/op
     p(99.9990) =     16.155 ms/op
     p(99.9999) =     16.155 ms/op
    p(100.0000) =     16.155 ms/op


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
# Warmup Iteration   1: 4.104 ±(99.9%) 0.110 ms/op
Iteration   1: 3.590 ±(99.9%) 0.038 ms/op
                 listUser·p0.00:   1.421 ms/op
                 listUser·p0.50:   3.539 ms/op
                 listUser·p0.90:   4.268 ms/op
                 listUser·p0.95:   4.591 ms/op
                 listUser·p0.99:   8.178 ms/op
                 listUser·p0.999:  15.024 ms/op
                 listUser·p0.9999: 16.220 ms/op
                 listUser·p1.00:   16.220 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8910
  mean =      3.590 ±(99.9%) 0.038 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 335 
    [ 2.500,  3.750) = 5196 
    [ 3.750,  5.000) = 3056 
    [ 5.000,  6.250) = 168 
    [ 6.250,  7.500) = 44 
    [ 7.500,  8.750) = 65 
    [ 8.750, 10.000) = 3 
    [10.000, 11.250) = 11 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 15 
    [15.000, 16.250) = 17 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.421 ms/op
     p(50.0000) =      3.539 ms/op
     p(90.0000) =      4.268 ms/op
     p(95.0000) =      4.591 ms/op
     p(99.0000) =      8.178 ms/op
     p(99.9000) =     15.024 ms/op
     p(99.9900) =     16.220 ms/op
     p(99.9990) =     16.220 ms/op
     p(99.9999) =     16.220 ms/op
    p(100.0000) =     16.220 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.050          ops/ms
ClientSimple.existUser                       thrpt         12.286          ops/ms
ClientSimple.getUser                         thrpt         14.476          ops/ms
ClientSimple.listUser                        thrpt          8.503          ops/ms
ClientSimple.createUser                       avgt          2.327           ms/op
ClientSimple.existUser                        avgt          1.879           ms/op
ClientSimple.getUser                          avgt          2.046           ms/op
ClientSimple.listUser                         avgt          3.478           ms/op
ClientSimple.createUser                     sample  15288   2.089 ± 0.028   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.624           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.884           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.576           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.076           ms/op
ClientSimple.createUser:createUser·p0.99    sample          4.695           ms/op
ClientSimple.createUser:createUser·p0.999   sample         17.138           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         17.350           ms/op
ClientSimple.createUser:createUser·p1.00    sample         17.367           ms/op
ClientSimple.existUser                      sample  16526   1.934 ± 0.017   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.540           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.839           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.400           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.735           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.243           ms/op
ClientSimple.existUser:existUser·p0.999     sample         11.853           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         12.252           ms/op
ClientSimple.existUser:existUser·p1.00      sample         12.337           ms/op
ClientSimple.getUser                        sample  14804   2.160 ± 0.022   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.700           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.985           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.888           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.178           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.547           ms/op
ClientSimple.getUser:getUser·p0.999         sample         15.896           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         16.115           ms/op
ClientSimple.getUser:getUser·p1.00          sample         16.155           ms/op
ClientSimple.listUser                       sample   8910   3.590 ± 0.038   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.421           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.539           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.268           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.591           ms/op
ClientSimple.listUser:listUser·p0.99        sample          8.178           ms/op
ClientSimple.listUser:listUser·p0.999       sample         15.024           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         16.220           ms/op
ClientSimple.listUser:listUser·p1.00        sample         16.220           ms/op

Benchmark result is saved to 1721412751836.json
