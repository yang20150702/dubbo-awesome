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
# Warmup Iteration   1: 0.930 ops/ms
Iteration   1: 6.182 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.182 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.632 ops/ms
Iteration   1: 12.498 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.498 ops/ms


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
# Warmup Iteration   1: 5.756 ops/ms
Iteration   1: 12.436 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.436 ops/ms


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
# Warmup Iteration   1: 5.227 ops/ms
Iteration   1: 8.392 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.392 ops/ms


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
# Warmup Iteration   1: 4.013 ±(99.9%) 0.071 ms/op
Iteration   1: 2.219 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.219 ms/op


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
# Warmup Iteration   1: 3.100 ±(99.9%) 0.049 ms/op
Iteration   1: 1.906 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.906 ms/op


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
# Warmup Iteration   1: 3.468 ±(99.9%) 0.061 ms/op
Iteration   1: 1.967 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.967 ms/op


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
# Warmup Iteration   1: 4.253 ±(99.9%) 0.077 ms/op
Iteration   1: 3.528 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.528 ms/op


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
# Warmup Iteration   1: 3.683 ±(99.9%) 0.102 ms/op
Iteration   1: 2.165 ±(99.9%) 0.034 ms/op
                 createUser·p0.00:   0.342 ms/op
                 createUser·p0.50:   2.034 ms/op
                 createUser·p0.90:   2.544 ms/op
                 createUser·p0.95:   2.871 ms/op
                 createUser·p0.99:   10.263 ms/op
                 createUser·p0.999:  15.237 ms/op
                 createUser·p0.9999: 15.803 ms/op
                 createUser·p1.00:   15.811 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14758
  mean =      2.165 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 419 
    [ 1.250,  2.500) = 12633 
    [ 2.500,  3.750) = 1344 
    [ 3.750,  5.000) = 50 
    [ 5.000,  6.250) = 114 
    [ 6.250,  7.500) = 6 
    [ 7.500,  8.750) = 32 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 63 
    [11.250, 12.500) = 14 
    [12.500, 13.750) = 36 
    [13.750, 15.000) = 29 
    [15.000, 16.250) = 18 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.342 ms/op
     p(50.0000) =      2.034 ms/op
     p(90.0000) =      2.544 ms/op
     p(95.0000) =      2.871 ms/op
     p(99.0000) =     10.263 ms/op
     p(99.9000) =     15.237 ms/op
     p(99.9900) =     15.803 ms/op
     p(99.9990) =     15.811 ms/op
     p(99.9999) =     15.811 ms/op
    p(100.0000) =     15.811 ms/op


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
# Warmup Iteration   1: 3.208 ±(99.9%) 0.080 ms/op
Iteration   1: 1.996 ±(99.9%) 0.027 ms/op
                 existUser·p0.00:   0.815 ms/op
                 existUser·p0.50:   1.907 ms/op
                 existUser·p0.90:   2.327 ms/op
                 existUser·p0.95:   2.486 ms/op
                 existUser·p0.99:   3.682 ms/op
                 existUser·p0.999:  21.135 ms/op
                 existUser·p0.9999: 21.365 ms/op
                 existUser·p1.00:   21.365 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16106
  mean =      1.996 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15332 
    [ 2.500,  5.000) = 683 
    [ 5.000,  7.500) = 23 
    [ 7.500, 10.000) = 4 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.815 ms/op
     p(50.0000) =      1.907 ms/op
     p(90.0000) =      2.327 ms/op
     p(95.0000) =      2.486 ms/op
     p(99.0000) =      3.682 ms/op
     p(99.9000) =     21.135 ms/op
     p(99.9900) =     21.365 ms/op
     p(99.9990) =     21.365 ms/op
     p(99.9999) =     21.365 ms/op
    p(100.0000) =     21.365 ms/op


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
# Warmup Iteration   1: 3.070 ±(99.9%) 0.077 ms/op
Iteration   1: 1.860 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   0.258 ms/op
                 getUser·p0.50:   1.765 ms/op
                 getUser·p0.90:   2.331 ms/op
                 getUser·p0.95:   2.597 ms/op
                 getUser·p0.99:   3.252 ms/op
                 getUser·p0.999:  12.672 ms/op
                 getUser·p0.9999: 13.520 ms/op
                 getUser·p1.00:   13.615 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 17293
  mean =      1.860 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 850 
    [ 1.250,  2.500) = 15382 
    [ 2.500,  3.750) = 925 
    [ 3.750,  5.000) = 30 
    [ 5.000,  6.250) = 36 
    [ 6.250,  7.500) = 5 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 30 
    [10.000, 11.250) = 2 
    [11.250, 12.500) = 6 
    [12.500, 13.750) = 26 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.258 ms/op
     p(50.0000) =      1.765 ms/op
     p(90.0000) =      2.331 ms/op
     p(95.0000) =      2.597 ms/op
     p(99.0000) =      3.252 ms/op
     p(99.9000) =     12.672 ms/op
     p(99.9900) =     13.520 ms/op
     p(99.9990) =     13.615 ms/op
     p(99.9999) =     13.615 ms/op
    p(100.0000) =     13.615 ms/op


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
# Warmup Iteration   1: 5.055 ±(99.9%) 0.151 ms/op
Iteration   1: 3.595 ±(99.9%) 0.034 ms/op
                 listUser·p0.00:   1.029 ms/op
                 listUser·p0.50:   3.650 ms/op
                 listUser·p0.90:   4.604 ms/op
                 listUser·p0.95:   4.981 ms/op
                 listUser·p0.99:   6.412 ms/op
                 listUser·p0.999:  10.018 ms/op
                 listUser·p0.9999: 11.764 ms/op
                 listUser·p1.00:   11.764 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8903
  mean =      3.595 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2 
    [ 1.250,  2.500) = 1190 
    [ 2.500,  3.750) = 3692 
    [ 3.750,  5.000) = 3591 
    [ 5.000,  6.250) = 334 
    [ 6.250,  7.500) = 59 
    [ 7.500,  8.750) = 3 
    [ 8.750, 10.000) = 23 
    [10.000, 11.250) = 7 
    [11.250, 12.500) = 2 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.029 ms/op
     p(50.0000) =      3.650 ms/op
     p(90.0000) =      4.604 ms/op
     p(95.0000) =      4.981 ms/op
     p(99.0000) =      6.412 ms/op
     p(99.9000) =     10.018 ms/op
     p(99.9900) =     11.764 ms/op
     p(99.9990) =     11.764 ms/op
     p(99.9999) =     11.764 ms/op
    p(100.0000) =     11.764 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.182          ops/ms
ClientSimple.existUser                       thrpt         12.498          ops/ms
ClientSimple.getUser                         thrpt         12.436          ops/ms
ClientSimple.listUser                        thrpt          8.392          ops/ms
ClientSimple.createUser                       avgt          2.219           ms/op
ClientSimple.existUser                        avgt          1.906           ms/op
ClientSimple.getUser                          avgt          1.967           ms/op
ClientSimple.listUser                         avgt          3.528           ms/op
ClientSimple.createUser                     sample  14758   2.165 ± 0.034   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.342           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.034           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.544           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.871           ms/op
ClientSimple.createUser:createUser·p0.99    sample         10.263           ms/op
ClientSimple.createUser:createUser·p0.999   sample         15.237           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         15.803           ms/op
ClientSimple.createUser:createUser·p1.00    sample         15.811           ms/op
ClientSimple.existUser                      sample  16106   1.996 ± 0.027   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.815           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.907           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.327           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.486           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.682           ms/op
ClientSimple.existUser:existUser·p0.999     sample         21.135           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         21.365           ms/op
ClientSimple.existUser:existUser·p1.00      sample         21.365           ms/op
ClientSimple.getUser                        sample  17293   1.860 ± 0.018   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.258           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.765           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.331           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.597           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.252           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.672           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         13.520           ms/op
ClientSimple.getUser:getUser·p1.00          sample         13.615           ms/op
ClientSimple.listUser                       sample   8903   3.595 ± 0.034   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.029           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.650           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.604           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.981           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.412           ms/op
ClientSimple.listUser:listUser·p0.999       sample         10.018           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         11.764           ms/op
ClientSimple.listUser:listUser·p1.00        sample         11.764           ms/op

Benchmark result is saved to 1718626618058.json
