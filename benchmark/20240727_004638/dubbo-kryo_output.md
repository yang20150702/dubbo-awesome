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
# Warmup Iteration   1: 1.905 ops/ms
Iteration   1: 6.905 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.905 ops/ms


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
# Warmup Iteration   1: 6.723 ops/ms
Iteration   1: 13.202 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.202 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:09
# Fork: 1 of 1
# Warmup Iteration   1: 6.579 ops/ms
Iteration   1: 14.299 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  14.299 ops/ms


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
# Warmup Iteration   1: 4.912 ops/ms
Iteration   1: 8.296 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.296 ops/ms


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
# Warmup Iteration   1: 3.893 ±(99.9%) 0.082 ms/op
Iteration   1: 2.108 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.108 ms/op


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
# Warmup Iteration   1: 3.063 ±(99.9%) 0.050 ms/op
Iteration   1: 1.611 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.611 ms/op


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
# Warmup Iteration   1: 3.348 ±(99.9%) 0.066 ms/op
Iteration   1: 2.361 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.361 ms/op


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
# Warmup Iteration   1: 4.451 ±(99.9%) 0.095 ms/op
Iteration   1: 3.425 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.425 ms/op


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
# Warmup Iteration   1: 3.694 ±(99.9%) 0.101 ms/op
Iteration   1: 2.179 ±(99.9%) 0.037 ms/op
                 createUser·p0.00:   0.877 ms/op
                 createUser·p0.50:   2.001 ms/op
                 createUser·p0.90:   2.515 ms/op
                 createUser·p0.95:   2.724 ms/op
                 createUser·p0.99:   5.341 ms/op
                 createUser·p0.999:  22.315 ms/op
                 createUser·p0.9999: 22.398 ms/op
                 createUser·p1.00:   22.413 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14713
  mean =      2.179 ±(99.9%) 0.037 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13151 
    [ 2.500,  5.000) = 1413 
    [ 5.000,  7.500) = 21 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 96 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.877 ms/op
     p(50.0000) =      2.001 ms/op
     p(90.0000) =      2.515 ms/op
     p(95.0000) =      2.724 ms/op
     p(99.0000) =      5.341 ms/op
     p(99.9000) =     22.315 ms/op
     p(99.9900) =     22.398 ms/op
     p(99.9990) =     22.413 ms/op
     p(99.9999) =     22.413 ms/op
    p(100.0000) =     22.413 ms/op


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
# Warmup Iteration   1: 3.133 ±(99.9%) 0.070 ms/op
Iteration   1: 1.665 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   0.592 ms/op
                 existUser·p0.50:   1.505 ms/op
                 existUser·p0.90:   2.134 ms/op
                 existUser·p0.95:   2.318 ms/op
                 existUser·p0.99:   5.104 ms/op
                 existUser·p0.999:  13.982 ms/op
                 existUser·p0.9999: 15.263 ms/op
                 existUser·p1.00:   15.565 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 19197
  mean =      1.665 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1306 
    [ 1.250,  2.500) = 17299 
    [ 2.500,  3.750) = 393 
    [ 3.750,  5.000) = 5 
    [ 5.000,  6.250) = 95 
    [ 6.250,  7.500) = 34 
    [ 7.500,  8.750) = 33 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 7 
    [13.750, 15.000) = 23 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.592 ms/op
     p(50.0000) =      1.505 ms/op
     p(90.0000) =      2.134 ms/op
     p(95.0000) =      2.318 ms/op
     p(99.0000) =      5.104 ms/op
     p(99.9000) =     13.982 ms/op
     p(99.9900) =     15.263 ms/op
     p(99.9990) =     15.565 ms/op
     p(99.9999) =     15.565 ms/op
    p(100.0000) =     15.565 ms/op


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
# Warmup Iteration   1: 3.184 ±(99.9%) 0.082 ms/op
Iteration   1: 1.943 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   0.759 ms/op
                 getUser·p0.50:   1.825 ms/op
                 getUser·p0.90:   2.404 ms/op
                 getUser·p0.95:   2.609 ms/op
                 getUser·p0.99:   3.133 ms/op
                 getUser·p0.999:  16.908 ms/op
                 getUser·p0.9999: 17.620 ms/op
                 getUser·p1.00:   17.662 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16452
  mean =      1.943 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 131 
    [ 1.250,  2.500) = 15096 
    [ 2.500,  3.750) = 1103 
    [ 3.750,  5.000) = 83 
    [ 5.000,  6.250) = 6 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 25 
    [17.500, 18.750) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.759 ms/op
     p(50.0000) =      1.825 ms/op
     p(90.0000) =      2.404 ms/op
     p(95.0000) =      2.609 ms/op
     p(99.0000) =      3.133 ms/op
     p(99.9000) =     16.908 ms/op
     p(99.9900) =     17.620 ms/op
     p(99.9990) =     17.662 ms/op
     p(99.9999) =     17.662 ms/op
    p(100.0000) =     17.662 ms/op


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
# Warmup Iteration   1: 4.101 ±(99.9%) 0.120 ms/op
Iteration   1: 3.785 ±(99.9%) 0.056 ms/op
                 listUser·p0.00:   0.732 ms/op
                 listUser·p0.50:   3.690 ms/op
                 listUser·p0.90:   4.432 ms/op
                 listUser·p0.95:   4.964 ms/op
                 listUser·p0.99:   7.397 ms/op
                 listUser·p0.999:  25.681 ms/op
                 listUser·p0.9999: 27.329 ms/op
                 listUser·p1.00:   27.329 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8455
  mean =      3.785 ±(99.9%) 0.056 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 419 
    [ 2.500,  5.000) = 7626 
    [ 5.000,  7.500) = 332 
    [ 7.500, 10.000) = 46 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 25 

  Percentiles, ms/op:
      p(0.0000) =      0.732 ms/op
     p(50.0000) =      3.690 ms/op
     p(90.0000) =      4.432 ms/op
     p(95.0000) =      4.964 ms/op
     p(99.0000) =      7.397 ms/op
     p(99.9000) =     25.681 ms/op
     p(99.9900) =     27.329 ms/op
     p(99.9990) =     27.329 ms/op
     p(99.9999) =     27.329 ms/op
    p(100.0000) =     27.329 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.905          ops/ms
ClientSimple.existUser                       thrpt         13.202          ops/ms
ClientSimple.getUser                         thrpt         14.299          ops/ms
ClientSimple.listUser                        thrpt          8.296          ops/ms
ClientSimple.createUser                       avgt          2.108           ms/op
ClientSimple.existUser                        avgt          1.611           ms/op
ClientSimple.getUser                          avgt          2.361           ms/op
ClientSimple.listUser                         avgt          3.425           ms/op
ClientSimple.createUser                     sample  14713   2.179 ± 0.037   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.877           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.001           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.515           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.724           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.341           ms/op
ClientSimple.createUser:createUser·p0.999   sample         22.315           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         22.398           ms/op
ClientSimple.createUser:createUser·p1.00    sample         22.413           ms/op
ClientSimple.existUser                      sample  19197   1.665 ± 0.018   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.592           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.505           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.134           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.318           ms/op
ClientSimple.existUser:existUser·p0.99      sample          5.104           ms/op
ClientSimple.existUser:existUser·p0.999     sample         13.982           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         15.263           ms/op
ClientSimple.existUser:existUser·p1.00      sample         15.565           ms/op
ClientSimple.getUser                        sample  16452   1.943 ± 0.020   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.759           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.825           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.404           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.609           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.133           ms/op
ClientSimple.getUser:getUser·p0.999         sample         16.908           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         17.620           ms/op
ClientSimple.getUser:getUser·p1.00          sample         17.662           ms/op
ClientSimple.listUser                       sample   8455   3.785 ± 0.056   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.732           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.690           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.432           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.964           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.397           ms/op
ClientSimple.listUser:listUser·p0.999       sample         25.681           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         27.329           ms/op
ClientSimple.listUser:listUser·p1.00        sample         27.329           ms/op

Benchmark result is saved to 1722040925388.json
