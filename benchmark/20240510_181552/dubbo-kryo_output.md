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
# Warmup Iteration   1: 1.818 ops/ms
Iteration   1: 6.767 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.767 ops/ms


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
# Warmup Iteration   1: 6.338 ops/ms
Iteration   1: 14.191 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  14.191 ops/ms


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
# Warmup Iteration   1: 5.687 ops/ms
Iteration   1: 13.331 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.331 ops/ms


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
# Warmup Iteration   1: 5.122 ops/ms
Iteration   1: 7.952 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  7.952 ops/ms


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
# Warmup Iteration   1: 3.721 ±(99.9%) 0.066 ms/op
Iteration   1: 2.214 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.214 ms/op


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
# Warmup Iteration   1: 3.634 ±(99.9%) 0.066 ms/op
Iteration   1: 1.931 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.931 ms/op


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
# Warmup Iteration   1: 3.265 ±(99.9%) 0.051 ms/op
Iteration   1: 1.968 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.968 ms/op


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
# Warmup Iteration   1: 4.672 ±(99.9%) 0.091 ms/op
Iteration   1: 3.716 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.716 ms/op


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
# Warmup Iteration   1: 4.013 ±(99.9%) 0.107 ms/op
Iteration   1: 2.356 ±(99.9%) 0.039 ms/op
                 createUser·p0.00:   0.681 ms/op
                 createUser·p0.50:   2.212 ms/op
                 createUser·p0.90:   2.912 ms/op
                 createUser·p0.95:   3.133 ms/op
                 createUser·p0.99:   5.652 ms/op
                 createUser·p0.999:  24.478 ms/op
                 createUser·p0.9999: 25.327 ms/op
                 createUser·p1.00:   25.362 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13559
  mean =      2.356 ±(99.9%) 0.039 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9451 
    [ 2.500,  5.000) = 3899 
    [ 5.000,  7.500) = 109 
    [ 7.500, 10.000) = 28 
    [10.000, 12.500) = 31 
    [12.500, 15.000) = 9 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.681 ms/op
     p(50.0000) =      2.212 ms/op
     p(90.0000) =      2.912 ms/op
     p(95.0000) =      3.133 ms/op
     p(99.0000) =      5.652 ms/op
     p(99.9000) =     24.478 ms/op
     p(99.9900) =     25.327 ms/op
     p(99.9990) =     25.362 ms/op
     p(99.9999) =     25.362 ms/op
    p(100.0000) =     25.362 ms/op


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
# Warmup Iteration   1: 2.796 ±(99.9%) 0.069 ms/op
Iteration   1: 1.916 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.710 ms/op
                 existUser·p0.50:   1.851 ms/op
                 existUser·p0.90:   2.408 ms/op
                 existUser·p0.95:   2.592 ms/op
                 existUser·p0.99:   3.146 ms/op
                 existUser·p0.999:  6.070 ms/op
                 existUser·p0.9999: 9.306 ms/op
                 existUser·p1.00:   9.306 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16804
  mean =      1.916 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  1.000) = 57 
    [ 1.000,  2.000) = 10569 
    [ 2.000,  3.000) = 5947 
    [ 3.000,  4.000) = 83 
    [ 4.000,  5.000) = 39 
    [ 5.000,  6.000) = 77 
    [ 6.000,  7.000) = 29 
    [ 7.000,  8.000) = 0 
    [ 8.000,  9.000) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.710 ms/op
     p(50.0000) =      1.851 ms/op
     p(90.0000) =      2.408 ms/op
     p(95.0000) =      2.592 ms/op
     p(99.0000) =      3.146 ms/op
     p(99.9000) =      6.070 ms/op
     p(99.9900) =      9.306 ms/op
     p(99.9990) =      9.306 ms/op
     p(99.9999) =      9.306 ms/op
    p(100.0000) =      9.306 ms/op


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
# Warmup Iteration   1: 3.222 ±(99.9%) 0.085 ms/op
Iteration   1: 2.116 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   0.769 ms/op
                 getUser·p0.50:   2.021 ms/op
                 getUser·p0.90:   2.662 ms/op
                 getUser·p0.95:   2.892 ms/op
                 getUser·p0.99:   4.429 ms/op
                 getUser·p0.999:  13.712 ms/op
                 getUser·p0.9999: 14.000 ms/op
                 getUser·p1.00:   14.008 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15114
  mean =      2.116 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 41 
    [ 1.250,  2.500) = 12558 
    [ 2.500,  3.750) = 2308 
    [ 3.750,  5.000) = 109 
    [ 5.000,  6.250) = 61 
    [ 6.250,  7.500) = 4 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 18 
    [13.750, 15.000) = 14 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.769 ms/op
     p(50.0000) =      2.021 ms/op
     p(90.0000) =      2.662 ms/op
     p(95.0000) =      2.892 ms/op
     p(99.0000) =      4.429 ms/op
     p(99.9000) =     13.712 ms/op
     p(99.9900) =     14.000 ms/op
     p(99.9990) =     14.008 ms/op
     p(99.9999) =     14.008 ms/op
    p(100.0000) =     14.008 ms/op


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
# Warmup Iteration   1: 4.263 ±(99.9%) 0.130 ms/op
Iteration   1: 3.207 ±(99.9%) 0.045 ms/op
                 listUser·p0.00:   0.640 ms/op
                 listUser·p0.50:   2.974 ms/op
                 listUser·p0.90:   4.076 ms/op
                 listUser·p0.95:   4.907 ms/op
                 listUser·p0.99:   8.765 ms/op
                 listUser·p0.999:  17.891 ms/op
                 listUser·p0.9999: 18.219 ms/op
                 listUser·p1.00:   18.219 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9972
  mean =      3.207 ±(99.9%) 0.045 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 53 
    [ 1.250,  2.500) = 2028 
    [ 2.500,  3.750) = 6185 
    [ 3.750,  5.000) = 1242 
    [ 5.000,  6.250) = 224 
    [ 6.250,  7.500) = 89 
    [ 7.500,  8.750) = 51 
    [ 8.750, 10.000) = 8 
    [10.000, 11.250) = 35 
    [11.250, 12.500) = 26 
    [12.500, 13.750) = 10 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 5 
    [17.500, 18.750) = 16 

  Percentiles, ms/op:
      p(0.0000) =      0.640 ms/op
     p(50.0000) =      2.974 ms/op
     p(90.0000) =      4.076 ms/op
     p(95.0000) =      4.907 ms/op
     p(99.0000) =      8.765 ms/op
     p(99.9000) =     17.891 ms/op
     p(99.9900) =     18.219 ms/op
     p(99.9990) =     18.219 ms/op
     p(99.9999) =     18.219 ms/op
    p(100.0000) =     18.219 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.767          ops/ms
ClientSimple.existUser                       thrpt         14.191          ops/ms
ClientSimple.getUser                         thrpt         13.331          ops/ms
ClientSimple.listUser                        thrpt          7.952          ops/ms
ClientSimple.createUser                       avgt          2.214           ms/op
ClientSimple.existUser                        avgt          1.931           ms/op
ClientSimple.getUser                          avgt          1.968           ms/op
ClientSimple.listUser                         avgt          3.716           ms/op
ClientSimple.createUser                     sample  13559   2.356 ± 0.039   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.681           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.212           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.912           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.133           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.652           ms/op
ClientSimple.createUser:createUser·p0.999   sample         24.478           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         25.327           ms/op
ClientSimple.createUser:createUser·p1.00    sample         25.362           ms/op
ClientSimple.existUser                      sample  16804   1.916 ± 0.013   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.710           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.851           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.408           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.592           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.146           ms/op
ClientSimple.existUser:existUser·p0.999     sample          6.070           ms/op
ClientSimple.existUser:existUser·p0.9999    sample          9.306           ms/op
ClientSimple.existUser:existUser·p1.00      sample          9.306           ms/op
ClientSimple.getUser                        sample  15114   2.116 ± 0.020   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.769           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.021           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.662           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.892           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.429           ms/op
ClientSimple.getUser:getUser·p0.999         sample         13.712           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         14.000           ms/op
ClientSimple.getUser:getUser·p1.00          sample         14.008           ms/op
ClientSimple.listUser                       sample   9972   3.207 ± 0.045   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.640           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.974           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.076           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.907           ms/op
ClientSimple.listUser:listUser·p0.99        sample          8.765           ms/op
ClientSimple.listUser:listUser·p0.999       sample         17.891           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         18.219           ms/op
ClientSimple.listUser:listUser·p1.00        sample         18.219           ms/op

Benchmark result is saved to 1715364687054.json
