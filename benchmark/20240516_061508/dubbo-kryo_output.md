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
# Warmup Iteration   1: 1.872 ops/ms
Iteration   1: 7.194 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.194 ops/ms


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
# Warmup Iteration   1: 6.275 ops/ms
Iteration   1: 11.115 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.115 ops/ms


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
# Warmup Iteration   1: 5.631 ops/ms
Iteration   1: 11.803 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.803 ops/ms


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
# Warmup Iteration   1: 4.765 ops/ms
Iteration   1: 8.130 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.130 ops/ms


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
# Warmup Iteration   1: 4.112 ±(99.9%) 0.095 ms/op
Iteration   1: 2.419 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.419 ms/op


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
# Warmup Iteration   1: 3.697 ±(99.9%) 0.073 ms/op
Iteration   1: 1.738 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.738 ms/op


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
# Warmup Iteration   1: 3.453 ±(99.9%) 0.089 ms/op
Iteration   1: 2.157 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.157 ms/op


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
# Warmup Iteration   1: 4.321 ±(99.9%) 0.093 ms/op
Iteration   1: 3.328 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.328 ms/op


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
# Warmup Iteration   1: 3.358 ±(99.9%) 0.090 ms/op
Iteration   1: 2.386 ±(99.9%) 0.027 ms/op
                 createUser·p0.00:   0.712 ms/op
                 createUser·p0.50:   2.249 ms/op
                 createUser·p0.90:   2.818 ms/op
                 createUser·p0.95:   3.064 ms/op
                 createUser·p0.99:   6.243 ms/op
                 createUser·p0.999:  14.130 ms/op
                 createUser·p0.9999: 15.821 ms/op
                 createUser·p1.00:   15.827 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13393
  mean =      2.386 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 66 
    [ 1.250,  2.500) = 9902 
    [ 2.500,  3.750) = 3005 
    [ 3.750,  5.000) = 105 
    [ 5.000,  6.250) = 182 
    [ 6.250,  7.500) = 66 
    [ 7.500,  8.750) = 10 
    [ 8.750, 10.000) = 9 
    [10.000, 11.250) = 15 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 10 
    [13.750, 15.000) = 16 
    [15.000, 16.250) = 6 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.712 ms/op
     p(50.0000) =      2.249 ms/op
     p(90.0000) =      2.818 ms/op
     p(95.0000) =      3.064 ms/op
     p(99.0000) =      6.243 ms/op
     p(99.9000) =     14.130 ms/op
     p(99.9900) =     15.821 ms/op
     p(99.9990) =     15.827 ms/op
     p(99.9999) =     15.827 ms/op
    p(100.0000) =     15.827 ms/op


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
# Warmup Iteration   1: 3.163 ±(99.9%) 0.071 ms/op
Iteration   1: 2.029 ±(99.9%) 0.038 ms/op
                 existUser·p0.00:   0.470 ms/op
                 existUser·p0.50:   1.878 ms/op
                 existUser·p0.90:   2.544 ms/op
                 existUser·p0.95:   2.744 ms/op
                 existUser·p0.99:   3.260 ms/op
                 existUser·p0.999:  31.130 ms/op
                 existUser·p0.9999: 31.741 ms/op
                 existUser·p1.00:   31.949 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15755
  mean =      2.029 ±(99.9%) 0.038 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13940 
    [ 2.500,  5.000) = 1751 
    [ 5.000,  7.500) = 0 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 31 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 32 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.470 ms/op
     p(50.0000) =      1.878 ms/op
     p(90.0000) =      2.544 ms/op
     p(95.0000) =      2.744 ms/op
     p(99.0000) =      3.260 ms/op
     p(99.9000) =     31.130 ms/op
     p(99.9900) =     31.741 ms/op
     p(99.9990) =     31.949 ms/op
     p(99.9999) =     31.949 ms/op
    p(100.0000) =     31.949 ms/op


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
# Warmup Iteration   1: 3.136 ±(99.9%) 0.082 ms/op
Iteration   1: 1.896 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   0.589 ms/op
                 getUser·p0.50:   1.806 ms/op
                 getUser·p0.90:   2.327 ms/op
                 getUser·p0.95:   2.458 ms/op
                 getUser·p0.99:   3.040 ms/op
                 getUser·p0.999:  11.587 ms/op
                 getUser·p0.9999: 11.730 ms/op
                 getUser·p1.00:   11.764 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16879
  mean =      1.896 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 214 
    [ 1.250,  2.500) = 15974 
    [ 2.500,  3.750) = 571 
    [ 3.750,  5.000) = 55 
    [ 5.000,  6.250) = 1 
    [ 6.250,  7.500) = 32 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 12 
    [11.250, 12.500) = 20 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.589 ms/op
     p(50.0000) =      1.806 ms/op
     p(90.0000) =      2.327 ms/op
     p(95.0000) =      2.458 ms/op
     p(99.0000) =      3.040 ms/op
     p(99.9000) =     11.587 ms/op
     p(99.9900) =     11.730 ms/op
     p(99.9990) =     11.764 ms/op
     p(99.9999) =     11.764 ms/op
    p(100.0000) =     11.764 ms/op


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
# Warmup Iteration   1: 4.376 ±(99.9%) 0.129 ms/op
Iteration   1: 3.729 ±(99.9%) 0.032 ms/op
                 listUser·p0.00:   1.444 ms/op
                 listUser·p0.50:   3.682 ms/op
                 listUser·p0.90:   4.624 ms/op
                 listUser·p0.95:   5.265 ms/op
                 listUser·p0.99:   7.211 ms/op
                 listUser·p0.999:  8.645 ms/op
                 listUser·p0.9999: 8.815 ms/op
                 listUser·p1.00:   8.815 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8584
  mean =      3.729 ±(99.9%) 0.032 ms/op

  Histogram, ms/op:
    [1.000, 1.500) = 2 
    [1.500, 2.000) = 106 
    [2.000, 2.500) = 424 
    [2.500, 3.000) = 933 
    [3.000, 3.500) = 1627 
    [3.500, 4.000) = 3132 
    [4.000, 4.500) = 1325 
    [4.500, 5.000) = 486 
    [5.000, 5.500) = 169 
    [5.500, 6.000) = 102 
    [6.000, 6.500) = 94 
    [6.500, 7.000) = 76 
    [7.000, 7.500) = 66 
    [7.500, 8.000) = 19 
    [8.000, 8.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      1.444 ms/op
     p(50.0000) =      3.682 ms/op
     p(90.0000) =      4.624 ms/op
     p(95.0000) =      5.265 ms/op
     p(99.0000) =      7.211 ms/op
     p(99.9000) =      8.645 ms/op
     p(99.9900) =      8.815 ms/op
     p(99.9990) =      8.815 ms/op
     p(99.9999) =      8.815 ms/op
    p(100.0000) =      8.815 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.194          ops/ms
ClientSimple.existUser                       thrpt         11.115          ops/ms
ClientSimple.getUser                         thrpt         11.803          ops/ms
ClientSimple.listUser                        thrpt          8.130          ops/ms
ClientSimple.createUser                       avgt          2.419           ms/op
ClientSimple.existUser                        avgt          1.738           ms/op
ClientSimple.getUser                          avgt          2.157           ms/op
ClientSimple.listUser                         avgt          3.328           ms/op
ClientSimple.createUser                     sample  13393   2.386 ± 0.027   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.712           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.249           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.818           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.064           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.243           ms/op
ClientSimple.createUser:createUser·p0.999   sample         14.130           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         15.821           ms/op
ClientSimple.createUser:createUser·p1.00    sample         15.827           ms/op
ClientSimple.existUser                      sample  15755   2.029 ± 0.038   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.470           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.878           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.544           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.744           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.260           ms/op
ClientSimple.existUser:existUser·p0.999     sample         31.130           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         31.741           ms/op
ClientSimple.existUser:existUser·p1.00      sample         31.949           ms/op
ClientSimple.getUser                        sample  16879   1.896 ± 0.015   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.589           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.806           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.327           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.458           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.040           ms/op
ClientSimple.getUser:getUser·p0.999         sample         11.587           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         11.730           ms/op
ClientSimple.getUser:getUser·p1.00          sample         11.764           ms/op
ClientSimple.listUser                       sample   8584   3.729 ± 0.032   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.444           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.682           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.624           ms/op
ClientSimple.listUser:listUser·p0.95        sample          5.265           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.211           ms/op
ClientSimple.listUser:listUser·p0.999       sample          8.645           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          8.815           ms/op
ClientSimple.listUser:listUser·p1.00        sample          8.815           ms/op

Benchmark result is saved to 1715839837078.json
