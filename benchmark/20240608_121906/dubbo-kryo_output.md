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
# Warmup Iteration   1: 1.876 ops/ms
Iteration   1: 7.314 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.314 ops/ms


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
# Warmup Iteration   1: 6.521 ops/ms
Iteration   1: 12.720 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.720 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 5.866 ops/ms
Iteration   1: 13.060 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.060 ops/ms


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
# Warmup Iteration   1: 5.040 ops/ms
Iteration   1: 8.185 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.185 ops/ms


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
# Warmup Iteration   1: 3.706 ±(99.9%) 0.075 ms/op
Iteration   1: 1.941 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  1.941 ms/op


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
# Warmup Iteration   1: 3.392 ±(99.9%) 0.056 ms/op
Iteration   1: 1.946 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.946 ms/op


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
# Warmup Iteration   1: 3.519 ±(99.9%) 0.058 ms/op
Iteration   1: 1.989 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.989 ms/op


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
# Warmup Iteration   1: 4.441 ±(99.9%) 0.080 ms/op
Iteration   1: 3.612 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.612 ms/op


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
# Warmup Iteration   1: 3.539 ±(99.9%) 0.090 ms/op
Iteration   1: 2.446 ±(99.9%) 0.029 ms/op
                 createUser·p0.00:   0.473 ms/op
                 createUser·p0.50:   2.413 ms/op
                 createUser·p0.90:   2.884 ms/op
                 createUser·p0.95:   3.097 ms/op
                 createUser·p0.99:   6.607 ms/op
                 createUser·p0.999:  16.138 ms/op
                 createUser·p0.9999: 17.332 ms/op
                 createUser·p1.00:   17.596 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13047
  mean =      2.446 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 235 
    [ 1.250,  2.500) = 7396 
    [ 2.500,  3.750) = 5115 
    [ 3.750,  5.000) = 72 
    [ 5.000,  6.250) = 68 
    [ 6.250,  7.500) = 79 
    [ 7.500,  8.750) = 50 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 25 
    [16.250, 17.500) = 6 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.473 ms/op
     p(50.0000) =      2.413 ms/op
     p(90.0000) =      2.884 ms/op
     p(95.0000) =      3.097 ms/op
     p(99.0000) =      6.607 ms/op
     p(99.9000) =     16.138 ms/op
     p(99.9900) =     17.332 ms/op
     p(99.9990) =     17.596 ms/op
     p(99.9999) =     17.596 ms/op
    p(100.0000) =     17.596 ms/op


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
# Warmup Iteration   1: 3.173 ±(99.9%) 0.067 ms/op
Iteration   1: 2.140 ±(99.9%) 0.032 ms/op
                 existUser·p0.00:   0.599 ms/op
                 existUser·p0.50:   2.028 ms/op
                 existUser·p0.90:   2.630 ms/op
                 existUser·p0.95:   2.744 ms/op
                 existUser·p0.99:   3.997 ms/op
                 existUser·p0.999:  23.035 ms/op
                 existUser·p0.9999: 23.724 ms/op
                 existUser·p1.00:   23.790 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15036
  mean =      2.140 ±(99.9%) 0.032 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12163 
    [ 2.500,  5.000) = 2773 
    [ 5.000,  7.500) = 36 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.599 ms/op
     p(50.0000) =      2.028 ms/op
     p(90.0000) =      2.630 ms/op
     p(95.0000) =      2.744 ms/op
     p(99.0000) =      3.997 ms/op
     p(99.9000) =     23.035 ms/op
     p(99.9900) =     23.724 ms/op
     p(99.9990) =     23.790 ms/op
     p(99.9999) =     23.790 ms/op
    p(100.0000) =     23.790 ms/op


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
# Warmup Iteration   1: 3.399 ±(99.9%) 0.082 ms/op
Iteration   1: 2.173 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   0.587 ms/op
                 getUser·p0.50:   2.101 ms/op
                 getUser·p0.90:   2.630 ms/op
                 getUser·p0.95:   2.810 ms/op
                 getUser·p0.99:   3.609 ms/op
                 getUser·p0.999:  16.982 ms/op
                 getUser·p0.9999: 17.170 ms/op
                 getUser·p1.00:   17.170 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14735
  mean =      2.173 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 97 
    [ 1.250,  2.500) = 12209 
    [ 2.500,  3.750) = 2336 
    [ 3.750,  5.000) = 21 
    [ 5.000,  6.250) = 17 
    [ 6.250,  7.500) = 20 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 32 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.587 ms/op
     p(50.0000) =      2.101 ms/op
     p(90.0000) =      2.630 ms/op
     p(95.0000) =      2.810 ms/op
     p(99.0000) =      3.609 ms/op
     p(99.9000) =     16.982 ms/op
     p(99.9900) =     17.170 ms/op
     p(99.9990) =     17.170 ms/op
     p(99.9999) =     17.170 ms/op
    p(100.0000) =     17.170 ms/op


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
# Warmup Iteration   1: 4.347 ±(99.9%) 0.135 ms/op
Iteration   1: 3.486 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   0.818 ms/op
                 listUser·p0.50:   3.496 ms/op
                 listUser·p0.90:   4.350 ms/op
                 listUser·p0.95:   4.809 ms/op
                 listUser·p0.99:   6.011 ms/op
                 listUser·p0.999:  7.191 ms/op
                 listUser·p0.9999: 7.913 ms/op
                 listUser·p1.00:   7.913 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9174
  mean =      3.486 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 3 
    [1.000, 1.500) = 10 
    [1.500, 2.000) = 69 
    [2.000, 2.500) = 324 
    [2.500, 3.000) = 2554 
    [3.000, 3.500) = 1646 
    [3.500, 4.000) = 2607 
    [4.000, 4.500) = 1239 
    [4.500, 5.000) = 362 
    [5.000, 5.500) = 199 
    [5.500, 6.000) = 68 
    [6.000, 6.500) = 52 
    [6.500, 7.000) = 4 
    [7.000, 7.500) = 34 

  Percentiles, ms/op:
      p(0.0000) =      0.818 ms/op
     p(50.0000) =      3.496 ms/op
     p(90.0000) =      4.350 ms/op
     p(95.0000) =      4.809 ms/op
     p(99.0000) =      6.011 ms/op
     p(99.9000) =      7.191 ms/op
     p(99.9900) =      7.913 ms/op
     p(99.9990) =      7.913 ms/op
     p(99.9999) =      7.913 ms/op
    p(100.0000) =      7.913 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.314          ops/ms
ClientSimple.existUser                       thrpt         12.720          ops/ms
ClientSimple.getUser                         thrpt         13.060          ops/ms
ClientSimple.listUser                        thrpt          8.185          ops/ms
ClientSimple.createUser                       avgt          1.941           ms/op
ClientSimple.existUser                        avgt          1.946           ms/op
ClientSimple.getUser                          avgt          1.989           ms/op
ClientSimple.listUser                         avgt          3.612           ms/op
ClientSimple.createUser                     sample  13047   2.446 ± 0.029   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.473           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.413           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.884           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.097           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.607           ms/op
ClientSimple.createUser:createUser·p0.999   sample         16.138           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         17.332           ms/op
ClientSimple.createUser:createUser·p1.00    sample         17.596           ms/op
ClientSimple.existUser                      sample  15036   2.140 ± 0.032   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.599           ms/op
ClientSimple.existUser:existUser·p0.50      sample          2.028           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.630           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.744           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.997           ms/op
ClientSimple.existUser:existUser·p0.999     sample         23.035           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         23.724           ms/op
ClientSimple.existUser:existUser·p1.00      sample         23.790           ms/op
ClientSimple.getUser                        sample  14735   2.173 ± 0.023   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.587           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.101           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.630           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.810           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.609           ms/op
ClientSimple.getUser:getUser·p0.999         sample         16.982           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         17.170           ms/op
ClientSimple.getUser:getUser·p1.00          sample         17.170           ms/op
ClientSimple.listUser                       sample   9174   3.486 ± 0.027   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.818           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.496           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.350           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.809           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.011           ms/op
ClientSimple.listUser:listUser·p0.999       sample          7.191           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          7.913           ms/op
ClientSimple.listUser:listUser·p1.00        sample          7.913           ms/op

Benchmark result is saved to 1717848892324.json
