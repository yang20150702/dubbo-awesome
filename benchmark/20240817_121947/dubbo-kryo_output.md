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
# Warmup Iteration   1: 1.066 ops/ms
Iteration   1: 6.268 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.268 ops/ms


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
# Warmup Iteration   1: 6.442 ops/ms
Iteration   1: 12.854 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.854 ops/ms


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
# Warmup Iteration   1: 6.019 ops/ms
Iteration   1: 13.269 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.269 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:02
# Fork: 1 of 1
# Warmup Iteration   1: 5.069 ops/ms
Iteration   1: 8.790 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.790 ops/ms


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
# Warmup Iteration   1: 3.608 ±(99.9%) 0.060 ms/op
Iteration   1: 2.092 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.092 ms/op


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
# Warmup Iteration   1: 3.112 ±(99.9%) 0.047 ms/op
Iteration   1: 1.886 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.886 ms/op


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
# Warmup Iteration   1: 3.287 ±(99.9%) 0.058 ms/op
Iteration   1: 1.887 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.887 ms/op


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
# Warmup Iteration   1: 4.473 ±(99.9%) 0.085 ms/op
Iteration   1: 3.566 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.566 ms/op


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
# Warmup Iteration   1: 3.446 ±(99.9%) 0.081 ms/op
Iteration   1: 2.171 ±(99.9%) 0.033 ms/op
                 createUser·p0.00:   0.435 ms/op
                 createUser·p0.50:   1.946 ms/op
                 createUser·p0.90:   2.761 ms/op
                 createUser·p0.95:   2.998 ms/op
                 createUser·p0.99:   7.733 ms/op
                 createUser·p0.999:  16.351 ms/op
                 createUser·p0.9999: 26.462 ms/op
                 createUser·p1.00:   26.542 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14887
  mean =      2.171 ±(99.9%) 0.033 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11903 
    [ 2.500,  5.000) = 2653 
    [ 5.000,  7.500) = 167 
    [ 7.500, 10.000) = 67 
    [10.000, 12.500) = 65 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 29 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.435 ms/op
     p(50.0000) =      1.946 ms/op
     p(90.0000) =      2.761 ms/op
     p(95.0000) =      2.998 ms/op
     p(99.0000) =      7.733 ms/op
     p(99.9000) =     16.351 ms/op
     p(99.9900) =     26.462 ms/op
     p(99.9990) =     26.542 ms/op
     p(99.9999) =     26.542 ms/op
    p(100.0000) =     26.542 ms/op


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

# Run progress: 75.00% complete, ETA 00:00:20
# Fork: 1 of 1
# Warmup Iteration   1: 2.914 ±(99.9%) 0.068 ms/op
Iteration   1: 2.010 ±(99.9%) 0.032 ms/op
                 existUser·p0.00:   0.202 ms/op
                 existUser·p0.50:   1.872 ms/op
                 existUser·p0.90:   2.425 ms/op
                 existUser·p0.95:   2.648 ms/op
                 existUser·p0.99:   4.973 ms/op
                 existUser·p0.999:  24.216 ms/op
                 existUser·p0.9999: 25.327 ms/op
                 existUser·p1.00:   25.985 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15909
  mean =      2.010 ±(99.9%) 0.032 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14786 
    [ 2.500,  5.000) = 976 
    [ 5.000,  7.500) = 83 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 10 
    [12.500, 15.000) = 22 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.202 ms/op
     p(50.0000) =      1.872 ms/op
     p(90.0000) =      2.425 ms/op
     p(95.0000) =      2.648 ms/op
     p(99.0000) =      4.973 ms/op
     p(99.9000) =     24.216 ms/op
     p(99.9900) =     25.327 ms/op
     p(99.9990) =     25.985 ms/op
     p(99.9999) =     25.985 ms/op
    p(100.0000) =     25.985 ms/op


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
# Warmup Iteration   1: 3.216 ±(99.9%) 0.083 ms/op
Iteration   1: 2.055 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   0.571 ms/op
                 getUser·p0.50:   1.958 ms/op
                 getUser·p0.90:   2.470 ms/op
                 getUser·p0.95:   2.695 ms/op
                 getUser·p0.99:   3.288 ms/op
                 getUser·p0.999:  15.598 ms/op
                 getUser·p0.9999: 17.717 ms/op
                 getUser·p1.00:   17.826 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15536
  mean =      2.055 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 41 
    [ 1.250,  2.500) = 14121 
    [ 2.500,  3.750) = 1260 
    [ 3.750,  5.000) = 29 
    [ 5.000,  6.250) = 3 
    [ 6.250,  7.500) = 19 
    [ 7.500,  8.750) = 16 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 13 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 24 
    [16.250, 17.500) = 4 
    [17.500, 18.750) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.571 ms/op
     p(50.0000) =      1.958 ms/op
     p(90.0000) =      2.470 ms/op
     p(95.0000) =      2.695 ms/op
     p(99.0000) =      3.288 ms/op
     p(99.9000) =     15.598 ms/op
     p(99.9900) =     17.717 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.492 ±(99.9%) 0.154 ms/op
Iteration   1: 3.305 ±(99.9%) 0.034 ms/op
                 listUser·p0.00:   0.939 ms/op
                 listUser·p0.50:   3.240 ms/op
                 listUser·p0.90:   4.174 ms/op
                 listUser·p0.95:   4.489 ms/op
                 listUser·p0.99:   7.160 ms/op
                 listUser·p0.999:  13.812 ms/op
                 listUser·p0.9999: 13.910 ms/op
                 listUser·p1.00:   13.910 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9680
  mean =      3.305 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 5 
    [ 1.250,  2.500) = 1729 
    [ 2.500,  3.750) = 5523 
    [ 3.750,  5.000) = 2204 
    [ 5.000,  6.250) = 81 
    [ 6.250,  7.500) = 96 
    [ 7.500,  8.750) = 8 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 15 
    [13.750, 15.000) = 17 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.939 ms/op
     p(50.0000) =      3.240 ms/op
     p(90.0000) =      4.174 ms/op
     p(95.0000) =      4.489 ms/op
     p(99.0000) =      7.160 ms/op
     p(99.9000) =     13.812 ms/op
     p(99.9900) =     13.910 ms/op
     p(99.9990) =     13.910 ms/op
     p(99.9999) =     13.910 ms/op
    p(100.0000) =     13.910 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.268          ops/ms
ClientSimple.existUser                       thrpt         12.854          ops/ms
ClientSimple.getUser                         thrpt         13.269          ops/ms
ClientSimple.listUser                        thrpt          8.790          ops/ms
ClientSimple.createUser                       avgt          2.092           ms/op
ClientSimple.existUser                        avgt          1.886           ms/op
ClientSimple.getUser                          avgt          1.887           ms/op
ClientSimple.listUser                         avgt          3.566           ms/op
ClientSimple.createUser                     sample  14887   2.171 ± 0.033   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.435           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.946           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.761           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.998           ms/op
ClientSimple.createUser:createUser·p0.99    sample          7.733           ms/op
ClientSimple.createUser:createUser·p0.999   sample         16.351           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         26.462           ms/op
ClientSimple.createUser:createUser·p1.00    sample         26.542           ms/op
ClientSimple.existUser                      sample  15909   2.010 ± 0.032   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.202           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.872           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.425           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.648           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.973           ms/op
ClientSimple.existUser:existUser·p0.999     sample         24.216           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         25.327           ms/op
ClientSimple.existUser:existUser·p1.00      sample         25.985           ms/op
ClientSimple.getUser                        sample  15536   2.055 ± 0.022   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.571           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.958           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.470           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.695           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.288           ms/op
ClientSimple.getUser:getUser·p0.999         sample         15.598           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         17.717           ms/op
ClientSimple.getUser:getUser·p1.00          sample         17.826           ms/op
ClientSimple.listUser                       sample   9680   3.305 ± 0.034   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.939           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.240           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.174           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.489           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.160           ms/op
ClientSimple.listUser:listUser·p0.999       sample         13.812           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         13.910           ms/op
ClientSimple.listUser:listUser·p1.00        sample         13.910           ms/op

Benchmark result is saved to 1723896927860.json
