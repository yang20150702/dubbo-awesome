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
# Warmup Iteration   1: 1.902 ops/ms
Iteration   1: 6.446 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.446 ops/ms


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
# Warmup Iteration   1: 6.016 ops/ms
Iteration   1: 11.610 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.610 ops/ms


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
# Warmup Iteration   1: 5.781 ops/ms
Iteration   1: 12.404 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.404 ops/ms


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
# Warmup Iteration   1: 3.565 ops/ms
Iteration   1: 7.854 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  7.854 ops/ms


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
# Warmup Iteration   1: 4.450 ±(99.9%) 0.083 ms/op
Iteration   1: 2.155 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.155 ms/op


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
# Warmup Iteration   1: 3.125 ±(99.9%) 0.049 ms/op
Iteration   1: 2.285 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.285 ms/op


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
# Warmup Iteration   1: 3.392 ±(99.9%) 0.064 ms/op
Iteration   1: 2.085 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.085 ms/op


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
# Warmup Iteration   1: 4.597 ±(99.9%) 0.113 ms/op
Iteration   1: 3.171 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.171 ms/op


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
# Warmup Iteration   1: 3.530 ±(99.9%) 0.111 ms/op
Iteration   1: 2.128 ±(99.9%) 0.034 ms/op
                 createUser·p0.00:   0.571 ms/op
                 createUser·p0.50:   1.921 ms/op
                 createUser·p0.90:   2.621 ms/op
                 createUser·p0.95:   2.830 ms/op
                 createUser·p0.99:   8.290 ms/op
                 createUser·p0.999:  17.136 ms/op
                 createUser·p0.9999: 18.432 ms/op
                 createUser·p1.00:   18.481 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15022
  mean =      2.128 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 283 
    [ 1.250,  2.500) = 12611 
    [ 2.500,  3.750) = 1855 
    [ 3.750,  5.000) = 54 
    [ 5.000,  6.250) = 55 
    [ 6.250,  7.500) = 4 
    [ 7.500,  8.750) = 13 
    [ 8.750, 10.000) = 19 
    [10.000, 11.250) = 27 
    [11.250, 12.500) = 5 
    [12.500, 13.750) = 9 
    [13.750, 15.000) = 50 
    [15.000, 16.250) = 9 
    [16.250, 17.500) = 17 
    [17.500, 18.750) = 11 

  Percentiles, ms/op:
      p(0.0000) =      0.571 ms/op
     p(50.0000) =      1.921 ms/op
     p(90.0000) =      2.621 ms/op
     p(95.0000) =      2.830 ms/op
     p(99.0000) =      8.290 ms/op
     p(99.9000) =     17.136 ms/op
     p(99.9900) =     18.432 ms/op
     p(99.9990) =     18.481 ms/op
     p(99.9999) =     18.481 ms/op
    p(100.0000) =     18.481 ms/op


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
# Warmup Iteration   1: 3.109 ±(99.9%) 0.066 ms/op
Iteration   1: 1.979 ±(99.9%) 0.031 ms/op
                 existUser·p0.00:   0.503 ms/op
                 existUser·p0.50:   1.858 ms/op
                 existUser·p0.90:   2.380 ms/op
                 existUser·p0.95:   2.552 ms/op
                 existUser·p0.99:   3.650 ms/op
                 existUser·p0.999:  21.889 ms/op
                 existUser·p0.9999: 22.438 ms/op
                 existUser·p1.00:   22.479 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16177
  mean =      1.979 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15160 
    [ 2.500,  5.000) = 939 
    [ 5.000,  7.500) = 8 
    [ 7.500, 10.000) = 5 
    [10.000, 12.500) = 1 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 11 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.503 ms/op
     p(50.0000) =      1.858 ms/op
     p(90.0000) =      2.380 ms/op
     p(95.0000) =      2.552 ms/op
     p(99.0000) =      3.650 ms/op
     p(99.9000) =     21.889 ms/op
     p(99.9900) =     22.438 ms/op
     p(99.9990) =     22.479 ms/op
     p(99.9999) =     22.479 ms/op
    p(100.0000) =     22.479 ms/op


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
# Warmup Iteration   1: 3.216 ±(99.9%) 0.084 ms/op
Iteration   1: 2.039 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   0.312 ms/op
                 getUser·p0.50:   1.952 ms/op
                 getUser·p0.90:   2.519 ms/op
                 getUser·p0.95:   2.757 ms/op
                 getUser·p0.99:   4.132 ms/op
                 getUser·p0.999:  14.063 ms/op
                 getUser·p0.9999: 14.513 ms/op
                 getUser·p1.00:   14.615 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15656
  mean =      2.039 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 250 
    [ 1.250,  2.500) = 13748 
    [ 2.500,  3.750) = 1423 
    [ 3.750,  5.000) = 116 
    [ 5.000,  6.250) = 46 
    [ 6.250,  7.500) = 36 
    [ 7.500,  8.750) = 5 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.312 ms/op
     p(50.0000) =      1.952 ms/op
     p(90.0000) =      2.519 ms/op
     p(95.0000) =      2.757 ms/op
     p(99.0000) =      4.132 ms/op
     p(99.9000) =     14.063 ms/op
     p(99.9900) =     14.513 ms/op
     p(99.9990) =     14.615 ms/op
     p(99.9999) =     14.615 ms/op
    p(100.0000) =     14.615 ms/op


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
# Warmup Iteration   1: 4.394 ±(99.9%) 0.118 ms/op
Iteration   1: 3.873 ±(99.9%) 0.048 ms/op
                 listUser·p0.00:   1.120 ms/op
                 listUser·p0.50:   3.670 ms/op
                 listUser·p0.90:   4.473 ms/op
                 listUser·p0.95:   5.475 ms/op
                 listUser·p0.99:   9.953 ms/op
                 listUser·p0.999:  16.138 ms/op
                 listUser·p0.9999: 17.957 ms/op
                 listUser·p1.00:   17.957 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8252
  mean =      3.873 ±(99.9%) 0.048 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3 
    [ 1.250,  2.500) = 213 
    [ 2.500,  3.750) = 4292 
    [ 3.750,  5.000) = 3137 
    [ 5.000,  6.250) = 290 
    [ 6.250,  7.500) = 161 
    [ 7.500,  8.750) = 38 
    [ 8.750, 10.000) = 38 
    [10.000, 11.250) = 12 
    [11.250, 12.500) = 31 
    [12.500, 13.750) = 2 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 31 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 4 

  Percentiles, ms/op:
      p(0.0000) =      1.120 ms/op
     p(50.0000) =      3.670 ms/op
     p(90.0000) =      4.473 ms/op
     p(95.0000) =      5.475 ms/op
     p(99.0000) =      9.953 ms/op
     p(99.9000) =     16.138 ms/op
     p(99.9900) =     17.957 ms/op
     p(99.9990) =     17.957 ms/op
     p(99.9999) =     17.957 ms/op
    p(100.0000) =     17.957 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.446          ops/ms
ClientSimple.existUser                       thrpt         11.610          ops/ms
ClientSimple.getUser                         thrpt         12.404          ops/ms
ClientSimple.listUser                        thrpt          7.854          ops/ms
ClientSimple.createUser                       avgt          2.155           ms/op
ClientSimple.existUser                        avgt          2.285           ms/op
ClientSimple.getUser                          avgt          2.085           ms/op
ClientSimple.listUser                         avgt          3.171           ms/op
ClientSimple.createUser                     sample  15022   2.128 ± 0.034   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.571           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.921           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.621           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.830           ms/op
ClientSimple.createUser:createUser·p0.99    sample          8.290           ms/op
ClientSimple.createUser:createUser·p0.999   sample         17.136           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         18.432           ms/op
ClientSimple.createUser:createUser·p1.00    sample         18.481           ms/op
ClientSimple.existUser                      sample  16177   1.979 ± 0.031   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.503           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.858           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.380           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.552           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.650           ms/op
ClientSimple.existUser:existUser·p0.999     sample         21.889           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         22.438           ms/op
ClientSimple.existUser:existUser·p1.00      sample         22.479           ms/op
ClientSimple.getUser                        sample  15656   2.039 ± 0.020   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.312           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.952           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.519           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.757           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.132           ms/op
ClientSimple.getUser:getUser·p0.999         sample         14.063           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         14.513           ms/op
ClientSimple.getUser:getUser·p1.00          sample         14.615           ms/op
ClientSimple.listUser                       sample   8252   3.873 ± 0.048   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.120           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.670           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.473           ms/op
ClientSimple.listUser:listUser·p0.95        sample          5.475           ms/op
ClientSimple.listUser:listUser·p0.99        sample          9.953           ms/op
ClientSimple.listUser:listUser·p0.999       sample         16.138           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         17.957           ms/op
ClientSimple.listUser:listUser·p1.00        sample         17.957           ms/op

Benchmark result is saved to 1715256919388.json
