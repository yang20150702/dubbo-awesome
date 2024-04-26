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
# Warmup Iteration   1: 1.883 ops/ms
Iteration   1: 7.065 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.065 ops/ms


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
# Warmup Iteration   1: 5.133 ops/ms
Iteration   1: 13.161 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.161 ops/ms


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
# Warmup Iteration   1: 5.490 ops/ms
Iteration   1: 11.919 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.919 ops/ms


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
# Warmup Iteration   1: 5.436 ops/ms
Iteration   1: 9.570 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.570 ops/ms


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
# Warmup Iteration   1: 3.689 ±(99.9%) 0.062 ms/op
Iteration   1: 2.324 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.324 ms/op


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
# Warmup Iteration   1: 3.236 ±(99.9%) 0.051 ms/op
Iteration   1: 1.786 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.786 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.377 ±(99.9%) 0.056 ms/op
Iteration   1: 1.902 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.902 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 4.895 ±(99.9%) 0.095 ms/op
Iteration   1: 3.414 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.414 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 3.615 ±(99.9%) 0.105 ms/op
Iteration   1: 2.166 ±(99.9%) 0.022 ms/op
                 createUser·p0.00:   0.663 ms/op
                 createUser·p0.50:   2.064 ms/op
                 createUser·p0.90:   2.789 ms/op
                 createUser·p0.95:   2.966 ms/op
                 createUser·p0.99:   3.890 ms/op
                 createUser·p0.999:  14.795 ms/op
                 createUser·p0.9999: 17.968 ms/op
                 createUser·p1.00:   18.809 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14752
  mean =      2.166 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 97 
    [ 1.250,  2.500) = 11241 
    [ 2.500,  3.750) = 3247 
    [ 3.750,  5.000) = 71 
    [ 5.000,  6.250) = 62 
    [ 6.250,  7.500) = 2 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 27 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 3 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.663 ms/op
     p(50.0000) =      2.064 ms/op
     p(90.0000) =      2.789 ms/op
     p(95.0000) =      2.966 ms/op
     p(99.0000) =      3.890 ms/op
     p(99.9000) =     14.795 ms/op
     p(99.9900) =     17.968 ms/op
     p(99.9990) =     18.809 ms/op
     p(99.9999) =     18.809 ms/op
    p(100.0000) =     18.809 ms/op


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
# Warmup Iteration   1: 2.965 ±(99.9%) 0.080 ms/op
Iteration   1: 1.985 ±(99.9%) 0.030 ms/op
                 existUser·p0.00:   0.510 ms/op
                 existUser·p0.50:   1.835 ms/op
                 existUser·p0.90:   2.474 ms/op
                 existUser·p0.95:   2.748 ms/op
                 existUser·p0.99:   4.612 ms/op
                 existUser·p0.999:  20.513 ms/op
                 existUser·p0.9999: 21.395 ms/op
                 existUser·p1.00:   21.496 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16148
  mean =      1.985 ±(99.9%) 0.030 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14618 
    [ 2.500,  5.000) = 1420 
    [ 5.000,  7.500) = 40 
    [ 7.500, 10.000) = 6 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.510 ms/op
     p(50.0000) =      1.835 ms/op
     p(90.0000) =      2.474 ms/op
     p(95.0000) =      2.748 ms/op
     p(99.0000) =      4.612 ms/op
     p(99.9000) =     20.513 ms/op
     p(99.9900) =     21.395 ms/op
     p(99.9990) =     21.496 ms/op
     p(99.9999) =     21.496 ms/op
    p(100.0000) =     21.496 ms/op


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
# Warmup Iteration   1: 3.300 ±(99.9%) 0.076 ms/op
Iteration   1: 2.182 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   0.709 ms/op
                 getUser·p0.50:   2.064 ms/op
                 getUser·p0.90:   2.687 ms/op
                 getUser·p0.95:   2.982 ms/op
                 getUser·p0.99:   4.891 ms/op
                 getUser·p0.999:  13.440 ms/op
                 getUser·p0.9999: 13.924 ms/op
                 getUser·p1.00:   14.008 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14661
  mean =      2.182 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 106 
    [ 1.250,  2.500) = 12043 
    [ 2.500,  3.750) = 2217 
    [ 3.750,  5.000) = 180 
    [ 5.000,  6.250) = 19 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 32 
    [ 8.750, 10.000) = 32 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 30 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.709 ms/op
     p(50.0000) =      2.064 ms/op
     p(90.0000) =      2.687 ms/op
     p(95.0000) =      2.982 ms/op
     p(99.0000) =      4.891 ms/op
     p(99.9000) =     13.440 ms/op
     p(99.9900) =     13.924 ms/op
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
# Warmup Iteration   1: 4.667 ±(99.9%) 0.222 ms/op
Iteration   1: 3.373 ±(99.9%) 0.042 ms/op
                 listUser·p0.00:   1.049 ms/op
                 listUser·p0.50:   3.297 ms/op
                 listUser·p0.90:   4.268 ms/op
                 listUser·p0.95:   4.750 ms/op
                 listUser·p0.99:   7.848 ms/op
                 listUser·p0.999:  15.879 ms/op
                 listUser·p0.9999: 17.727 ms/op
                 listUser·p1.00:   17.727 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9462
  mean =      3.373 ±(99.9%) 0.042 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 7 
    [ 1.250,  2.500) = 2160 
    [ 2.500,  3.750) = 4660 
    [ 3.750,  5.000) = 2236 
    [ 5.000,  6.250) = 186 
    [ 6.250,  7.500) = 107 
    [ 7.500,  8.750) = 42 
    [ 8.750, 10.000) = 29 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 2 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 29 
    [16.250, 17.500) = 2 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.049 ms/op
     p(50.0000) =      3.297 ms/op
     p(90.0000) =      4.268 ms/op
     p(95.0000) =      4.750 ms/op
     p(99.0000) =      7.848 ms/op
     p(99.9000) =     15.879 ms/op
     p(99.9900) =     17.727 ms/op
     p(99.9990) =     17.727 ms/op
     p(99.9999) =     17.727 ms/op
    p(100.0000) =     17.727 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.065          ops/ms
ClientSimple.existUser                       thrpt         13.161          ops/ms
ClientSimple.getUser                         thrpt         11.919          ops/ms
ClientSimple.listUser                        thrpt          9.570          ops/ms
ClientSimple.createUser                       avgt          2.324           ms/op
ClientSimple.existUser                        avgt          1.786           ms/op
ClientSimple.getUser                          avgt          1.902           ms/op
ClientSimple.listUser                         avgt          3.414           ms/op
ClientSimple.createUser                     sample  14752   2.166 ± 0.022   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.663           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.064           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.789           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.966           ms/op
ClientSimple.createUser:createUser·p0.99    sample          3.890           ms/op
ClientSimple.createUser:createUser·p0.999   sample         14.795           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         17.968           ms/op
ClientSimple.createUser:createUser·p1.00    sample         18.809           ms/op
ClientSimple.existUser                      sample  16148   1.985 ± 0.030   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.510           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.835           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.474           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.748           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.612           ms/op
ClientSimple.existUser:existUser·p0.999     sample         20.513           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         21.395           ms/op
ClientSimple.existUser:existUser·p1.00      sample         21.496           ms/op
ClientSimple.getUser                        sample  14661   2.182 ± 0.024   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.709           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.064           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.687           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.982           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.891           ms/op
ClientSimple.getUser:getUser·p0.999         sample         13.440           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         13.924           ms/op
ClientSimple.getUser:getUser·p1.00          sample         14.008           ms/op
ClientSimple.listUser                       sample   9462   3.373 ± 0.042   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.049           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.297           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.268           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.750           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.848           ms/op
ClientSimple.listUser:listUser·p0.999       sample         15.879           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         17.727           ms/op
ClientSimple.listUser:listUser·p1.00        sample         17.727           ms/op

Benchmark result is saved to 1714155047454.json
