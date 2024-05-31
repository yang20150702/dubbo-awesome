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
# Warmup Iteration   1: 1.804 ops/ms
Iteration   1: 7.697 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.697 ops/ms


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
# Warmup Iteration   1: 5.608 ops/ms
Iteration   1: 12.529 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.529 ops/ms


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
# Warmup Iteration   1: 4.957 ops/ms
Iteration   1: 13.114 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.114 ops/ms


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
# Warmup Iteration   1: 5.808 ops/ms
Iteration   1: 8.587 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.587 ops/ms


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
# Warmup Iteration   1: 3.416 ±(99.9%) 0.054 ms/op
Iteration   1: 2.125 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.125 ms/op


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
# Warmup Iteration   1: 3.084 ±(99.9%) 0.054 ms/op
Iteration   1: 1.818 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.818 ms/op


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
# Warmup Iteration   1: 3.465 ±(99.9%) 0.072 ms/op
Iteration   1: 2.150 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.150 ms/op


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
# Warmup Iteration   1: 4.278 ±(99.9%) 0.089 ms/op
Iteration   1: 3.429 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.429 ms/op


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
# Warmup Iteration   1: 3.566 ±(99.9%) 0.095 ms/op
Iteration   1: 2.290 ±(99.9%) 0.035 ms/op
                 createUser·p0.00:   0.407 ms/op
                 createUser·p0.50:   2.087 ms/op
                 createUser·p0.90:   2.773 ms/op
                 createUser·p0.95:   3.023 ms/op
                 createUser·p0.99:   9.519 ms/op
                 createUser·p0.999:  16.001 ms/op
                 createUser·p0.9999: 17.308 ms/op
                 createUser·p1.00:   17.334 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14039
  mean =      2.290 ±(99.9%) 0.035 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 339 
    [ 1.250,  2.500) = 10139 
    [ 2.500,  3.750) = 3167 
    [ 3.750,  5.000) = 172 
    [ 5.000,  6.250) = 27 
    [ 6.250,  7.500) = 11 
    [ 7.500,  8.750) = 15 
    [ 8.750, 10.000) = 41 
    [10.000, 11.250) = 49 
    [11.250, 12.500) = 15 
    [12.500, 13.750) = 30 
    [13.750, 15.000) = 12 
    [15.000, 16.250) = 10 
    [16.250, 17.500) = 12 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.407 ms/op
     p(50.0000) =      2.087 ms/op
     p(90.0000) =      2.773 ms/op
     p(95.0000) =      3.023 ms/op
     p(99.0000) =      9.519 ms/op
     p(99.9000) =     16.001 ms/op
     p(99.9900) =     17.308 ms/op
     p(99.9990) =     17.334 ms/op
     p(99.9999) =     17.334 ms/op
    p(100.0000) =     17.334 ms/op


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
# Warmup Iteration   1: 3.449 ±(99.9%) 0.085 ms/op
Iteration   1: 1.946 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   0.550 ms/op
                 existUser·p0.50:   1.821 ms/op
                 existUser·p0.90:   2.392 ms/op
                 existUser·p0.95:   2.597 ms/op
                 existUser·p0.99:   4.166 ms/op
                 existUser·p0.999:  10.666 ms/op
                 existUser·p0.9999: 10.770 ms/op
                 existUser·p1.00:   10.781 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16427
  mean =      1.946 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 298 
    [ 1.250,  2.500) = 15030 
    [ 2.500,  3.750) = 895 
    [ 3.750,  5.000) = 110 
    [ 5.000,  6.250) = 37 
    [ 6.250,  7.500) = 15 
    [ 7.500,  8.750) = 5 
    [ 8.750, 10.000) = 5 
    [10.000, 11.250) = 32 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.550 ms/op
     p(50.0000) =      1.821 ms/op
     p(90.0000) =      2.392 ms/op
     p(95.0000) =      2.597 ms/op
     p(99.0000) =      4.166 ms/op
     p(99.9000) =     10.666 ms/op
     p(99.9900) =     10.770 ms/op
     p(99.9990) =     10.781 ms/op
     p(99.9999) =     10.781 ms/op
    p(100.0000) =     10.781 ms/op


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
# Warmup Iteration   1: 3.378 ±(99.9%) 0.075 ms/op
Iteration   1: 2.195 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   0.437 ms/op
                 getUser·p0.50:   2.146 ms/op
                 getUser·p0.90:   2.707 ms/op
                 getUser·p0.95:   2.938 ms/op
                 getUser·p0.99:   4.051 ms/op
                 getUser·p0.999:  15.352 ms/op
                 getUser·p0.9999: 16.309 ms/op
                 getUser·p1.00:   16.384 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14573
  mean =      2.195 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 87 
    [ 1.250,  2.500) = 11953 
    [ 2.500,  3.750) = 2328 
    [ 3.750,  5.000) = 141 
    [ 5.000,  6.250) = 30 
    [ 6.250,  7.500) = 2 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 31 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.437 ms/op
     p(50.0000) =      2.146 ms/op
     p(90.0000) =      2.707 ms/op
     p(95.0000) =      2.938 ms/op
     p(99.0000) =      4.051 ms/op
     p(99.9000) =     15.352 ms/op
     p(99.9900) =     16.309 ms/op
     p(99.9990) =     16.384 ms/op
     p(99.9999) =     16.384 ms/op
    p(100.0000) =     16.384 ms/op


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
# Warmup Iteration   1: 4.610 ±(99.9%) 0.164 ms/op
Iteration   1: 3.473 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   1.036 ms/op
                 listUser·p0.50:   3.506 ms/op
                 listUser·p0.90:   4.182 ms/op
                 listUser·p0.95:   4.478 ms/op
                 listUser·p0.99:   5.767 ms/op
                 listUser·p0.999:  6.507 ms/op
                 listUser·p0.9999: 6.955 ms/op
                 listUser·p1.00:   6.955 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9206
  mean =      3.473 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [1.000, 1.500) = 25 
    [1.500, 2.000) = 83 
    [2.000, 2.500) = 662 
    [2.500, 3.000) = 1200 
    [3.000, 3.500) = 2578 
    [3.500, 4.000) = 3137 
    [4.000, 4.500) = 1080 
    [4.500, 5.000) = 266 
    [5.000, 5.500) = 38 
    [5.500, 6.000) = 90 
    [6.000, 6.500) = 38 

  Percentiles, ms/op:
      p(0.0000) =      1.036 ms/op
     p(50.0000) =      3.506 ms/op
     p(90.0000) =      4.182 ms/op
     p(95.0000) =      4.478 ms/op
     p(99.0000) =      5.767 ms/op
     p(99.9000) =      6.507 ms/op
     p(99.9900) =      6.955 ms/op
     p(99.9990) =      6.955 ms/op
     p(99.9999) =      6.955 ms/op
    p(100.0000) =      6.955 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.697          ops/ms
ClientSimple.existUser                       thrpt         12.529          ops/ms
ClientSimple.getUser                         thrpt         13.114          ops/ms
ClientSimple.listUser                        thrpt          8.587          ops/ms
ClientSimple.createUser                       avgt          2.125           ms/op
ClientSimple.existUser                        avgt          1.818           ms/op
ClientSimple.getUser                          avgt          2.150           ms/op
ClientSimple.listUser                         avgt          3.429           ms/op
ClientSimple.createUser                     sample  14039   2.290 ± 0.035   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.407           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.087           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.773           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.023           ms/op
ClientSimple.createUser:createUser·p0.99    sample          9.519           ms/op
ClientSimple.createUser:createUser·p0.999   sample         16.001           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         17.308           ms/op
ClientSimple.createUser:createUser·p1.00    sample         17.334           ms/op
ClientSimple.existUser                      sample  16427   1.946 ± 0.016   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.550           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.821           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.392           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.597           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.166           ms/op
ClientSimple.existUser:existUser·p0.999     sample         10.666           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         10.770           ms/op
ClientSimple.existUser:existUser·p1.00      sample         10.781           ms/op
ClientSimple.getUser                        sample  14573   2.195 ± 0.022   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.437           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.146           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.707           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.938           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.051           ms/op
ClientSimple.getUser:getUser·p0.999         sample         15.352           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         16.309           ms/op
ClientSimple.getUser:getUser·p1.00          sample         16.384           ms/op
ClientSimple.listUser                       sample   9206   3.473 ± 0.023   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.036           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.506           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.182           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.478           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.767           ms/op
ClientSimple.listUser:listUser·p0.999       sample          6.507           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          6.955           ms/op
ClientSimple.listUser:listUser·p1.00        sample          6.955           ms/op

Benchmark result is saved to 1717179104176.json
