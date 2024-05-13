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
# Warmup Iteration   1: 1.788 ops/ms
Iteration   1: 6.721 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.721 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:19
# Fork: 1 of 1
# Warmup Iteration   1: 5.212 ops/ms
Iteration   1: 13.193 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.193 ops/ms


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
# Warmup Iteration   1: 4.919 ops/ms
Iteration   1: 11.649 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.649 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.817 ops/ms
Iteration   1: 8.810 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.810 ops/ms


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
# Warmup Iteration   1: 3.850 ±(99.9%) 0.074 ms/op
Iteration   1: 2.150 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
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
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.906 ±(99.9%) 0.074 ms/op
Iteration   1: 2.080 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.080 ms/op


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
# Warmup Iteration   1: 3.447 ±(99.9%) 0.054 ms/op
Iteration   1: 2.139 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.139 ms/op


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
# Warmup Iteration   1: 5.443 ±(99.9%) 0.122 ms/op
Iteration   1: 3.625 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.625 ms/op


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
# Warmup Iteration   1: 3.527 ±(99.9%) 0.088 ms/op
Iteration   1: 2.030 ±(99.9%) 0.034 ms/op
                 createUser·p0.00:   0.635 ms/op
                 createUser·p0.50:   1.821 ms/op
                 createUser·p0.90:   2.544 ms/op
                 createUser·p0.95:   2.748 ms/op
                 createUser·p0.99:   7.141 ms/op
                 createUser·p0.999:  16.490 ms/op
                 createUser·p0.9999: 17.629 ms/op
                 createUser·p1.00:   17.629 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15766
  mean =      2.030 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 446 
    [ 1.250,  2.500) = 13508 
    [ 2.500,  3.750) = 1523 
    [ 3.750,  5.000) = 47 
    [ 5.000,  6.250) = 82 
    [ 6.250,  7.500) = 29 
    [ 7.500,  8.750) = 3 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 28 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 38 
    [16.250, 17.500) = 28 
    [17.500, 18.750) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.635 ms/op
     p(50.0000) =      1.821 ms/op
     p(90.0000) =      2.544 ms/op
     p(95.0000) =      2.748 ms/op
     p(99.0000) =      7.141 ms/op
     p(99.9000) =     16.490 ms/op
     p(99.9900) =     17.629 ms/op
     p(99.9990) =     17.629 ms/op
     p(99.9999) =     17.629 ms/op
    p(100.0000) =     17.629 ms/op


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
# Warmup Iteration   1: 2.991 ±(99.9%) 0.076 ms/op
Iteration   1: 1.920 ±(99.9%) 0.033 ms/op
                 existUser·p0.00:   0.345 ms/op
                 existUser·p0.50:   1.845 ms/op
                 existUser·p0.90:   2.327 ms/op
                 existUser·p0.95:   2.531 ms/op
                 existUser·p0.99:   4.276 ms/op
                 existUser·p0.999:  27.591 ms/op
                 existUser·p0.9999: 27.689 ms/op
                 existUser·p1.00:   27.689 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16667
  mean =      1.920 ±(99.9%) 0.033 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15768 
    [ 2.500,  5.000) = 818 
    [ 5.000,  7.500) = 17 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 30 
    [12.500, 15.000) = 2 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      0.345 ms/op
     p(50.0000) =      1.845 ms/op
     p(90.0000) =      2.327 ms/op
     p(95.0000) =      2.531 ms/op
     p(99.0000) =      4.276 ms/op
     p(99.9000) =     27.591 ms/op
     p(99.9900) =     27.689 ms/op
     p(99.9990) =     27.689 ms/op
     p(99.9999) =     27.689 ms/op
    p(100.0000) =     27.689 ms/op


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
# Warmup Iteration   1: 3.190 ±(99.9%) 0.077 ms/op
Iteration   1: 2.149 ±(99.9%) 0.035 ms/op
                 getUser·p0.00:   0.683 ms/op
                 getUser·p0.50:   1.970 ms/op
                 getUser·p0.90:   2.593 ms/op
                 getUser·p0.95:   2.851 ms/op
                 getUser·p0.99:   5.407 ms/op
                 getUser·p0.999:  24.194 ms/op
                 getUser·p0.9999: 31.723 ms/op
                 getUser·p1.00:   32.571 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14882
  mean =      2.149 ±(99.9%) 0.035 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12825 
    [ 2.500,  5.000) = 1890 
    [ 5.000,  7.500) = 97 
    [ 7.500, 10.000) = 5 
    [10.000, 12.500) = 11 
    [12.500, 15.000) = 21 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 1 
    [27.500, 30.000) = 1 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.683 ms/op
     p(50.0000) =      1.970 ms/op
     p(90.0000) =      2.593 ms/op
     p(95.0000) =      2.851 ms/op
     p(99.0000) =      5.407 ms/op
     p(99.9000) =     24.194 ms/op
     p(99.9900) =     31.723 ms/op
     p(99.9990) =     32.571 ms/op
     p(99.9999) =     32.571 ms/op
    p(100.0000) =     32.571 ms/op


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
# Warmup Iteration   1: 4.501 ±(99.9%) 0.149 ms/op
Iteration   1: 3.489 ±(99.9%) 0.033 ms/op
                 listUser·p0.00:   0.913 ms/op
                 listUser·p0.50:   3.465 ms/op
                 listUser·p0.90:   4.448 ms/op
                 listUser·p0.95:   4.841 ms/op
                 listUser·p0.99:   6.409 ms/op
                 listUser·p0.999:  11.578 ms/op
                 listUser·p0.9999: 15.041 ms/op
                 listUser·p1.00:   15.041 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9160
  mean =      3.489 ±(99.9%) 0.033 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 6 
    [ 1.250,  2.500) = 1027 
    [ 2.500,  3.750) = 4805 
    [ 3.750,  5.000) = 2989 
    [ 5.000,  6.250) = 235 
    [ 6.250,  7.500) = 52 
    [ 7.500,  8.750) = 11 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 16 
    [11.250, 12.500) = 18 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.913 ms/op
     p(50.0000) =      3.465 ms/op
     p(90.0000) =      4.448 ms/op
     p(95.0000) =      4.841 ms/op
     p(99.0000) =      6.409 ms/op
     p(99.9000) =     11.578 ms/op
     p(99.9900) =     15.041 ms/op
     p(99.9990) =     15.041 ms/op
     p(99.9999) =     15.041 ms/op
    p(100.0000) =     15.041 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.721          ops/ms
ClientSimple.existUser                       thrpt         13.193          ops/ms
ClientSimple.getUser                         thrpt         11.649          ops/ms
ClientSimple.listUser                        thrpt          8.810          ops/ms
ClientSimple.createUser                       avgt          2.150           ms/op
ClientSimple.existUser                        avgt          2.080           ms/op
ClientSimple.getUser                          avgt          2.139           ms/op
ClientSimple.listUser                         avgt          3.625           ms/op
ClientSimple.createUser                     sample  15766   2.030 ± 0.034   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.635           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.821           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.544           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.748           ms/op
ClientSimple.createUser:createUser·p0.99    sample          7.141           ms/op
ClientSimple.createUser:createUser·p0.999   sample         16.490           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         17.629           ms/op
ClientSimple.createUser:createUser·p1.00    sample         17.629           ms/op
ClientSimple.existUser                      sample  16667   1.920 ± 0.033   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.345           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.845           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.327           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.531           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.276           ms/op
ClientSimple.existUser:existUser·p0.999     sample         27.591           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         27.689           ms/op
ClientSimple.existUser:existUser·p1.00      sample         27.689           ms/op
ClientSimple.getUser                        sample  14882   2.149 ± 0.035   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.683           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.970           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.593           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.851           ms/op
ClientSimple.getUser:getUser·p0.99          sample          5.407           ms/op
ClientSimple.getUser:getUser·p0.999         sample         24.194           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         31.723           ms/op
ClientSimple.getUser:getUser·p1.00          sample         32.571           ms/op
ClientSimple.listUser                       sample   9160   3.489 ± 0.033   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.913           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.465           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.448           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.841           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.409           ms/op
ClientSimple.listUser:listUser·p0.999       sample         11.578           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         15.041           ms/op
ClientSimple.listUser:listUser·p1.00        sample         15.041           ms/op

Benchmark result is saved to 1715560816760.json
