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
# Warmup Iteration   1: 1.808 ops/ms
Iteration   1: 6.697 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.697 ops/ms


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
# Warmup Iteration   1: 5.037 ops/ms
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

# Run progress: 16.67% complete, ETA 00:01:11
# Fork: 1 of 1
# Warmup Iteration   1: 4.842 ops/ms
Iteration   1: 11.479 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.479 ops/ms


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
# Warmup Iteration   1: 4.060 ops/ms
Iteration   1: 8.595 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.595 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:57
# Fork: 1 of 1
# Warmup Iteration   1: 4.266 ±(99.9%) 0.082 ms/op
Iteration   1: 2.016 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.016 ms/op


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
# Warmup Iteration   1: 3.027 ±(99.9%) 0.053 ms/op
Iteration   1: 2.010 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.010 ms/op


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
# Warmup Iteration   1: 3.878 ±(99.9%) 0.079 ms/op
Iteration   1: 2.107 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.107 ms/op


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
# Warmup Iteration   1: 5.426 ±(99.9%) 0.119 ms/op
Iteration   1: 3.650 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.650 ms/op


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
# Warmup Iteration   1: 3.628 ±(99.9%) 0.096 ms/op
Iteration   1: 2.101 ±(99.9%) 0.027 ms/op
                 createUser·p0.00:   0.634 ms/op
                 createUser·p0.50:   1.956 ms/op
                 createUser·p0.90:   2.511 ms/op
                 createUser·p0.95:   3.002 ms/op
                 createUser·p0.99:   5.498 ms/op
                 createUser·p0.999:  16.550 ms/op
                 createUser·p0.9999: 18.022 ms/op
                 createUser·p1.00:   18.022 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15288
  mean =      2.101 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 212 
    [ 1.250,  2.500) = 13515 
    [ 2.500,  3.750) = 1094 
    [ 3.750,  5.000) = 264 
    [ 5.000,  6.250) = 95 
    [ 6.250,  7.500) = 41 
    [ 7.500,  8.750) = 3 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 21 
    [12.500, 13.750) = 4 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 14 
    [16.250, 17.500) = 21 
    [17.500, 18.750) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.634 ms/op
     p(50.0000) =      1.956 ms/op
     p(90.0000) =      2.511 ms/op
     p(95.0000) =      3.002 ms/op
     p(99.0000) =      5.498 ms/op
     p(99.9000) =     16.550 ms/op
     p(99.9900) =     18.022 ms/op
     p(99.9990) =     18.022 ms/op
     p(99.9999) =     18.022 ms/op
    p(100.0000) =     18.022 ms/op


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
# Warmup Iteration   1: 3.104 ±(99.9%) 0.099 ms/op
Iteration   1: 2.090 ±(99.9%) 0.034 ms/op
                 existUser·p0.00:   0.492 ms/op
                 existUser·p0.50:   2.036 ms/op
                 existUser·p0.90:   2.626 ms/op
                 existUser·p0.95:   2.847 ms/op
                 existUser·p0.99:   3.751 ms/op
                 existUser·p0.999:  23.495 ms/op
                 existUser·p0.9999: 23.829 ms/op
                 existUser·p1.00:   23.986 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15325
  mean =      2.090 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13125 
    [ 2.500,  5.000) = 2103 
    [ 5.000,  7.500) = 31 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 2 
    [12.500, 15.000) = 17 
    [15.000, 17.500) = 14 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.492 ms/op
     p(50.0000) =      2.036 ms/op
     p(90.0000) =      2.626 ms/op
     p(95.0000) =      2.847 ms/op
     p(99.0000) =      3.751 ms/op
     p(99.9000) =     23.495 ms/op
     p(99.9900) =     23.829 ms/op
     p(99.9990) =     23.986 ms/op
     p(99.9999) =     23.986 ms/op
    p(100.0000) =     23.986 ms/op


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
# Warmup Iteration   1: 3.610 ±(99.9%) 0.095 ms/op
Iteration   1: 1.881 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   1.001 ms/op
                 getUser·p0.50:   1.706 ms/op
                 getUser·p0.90:   2.482 ms/op
                 getUser·p0.95:   2.793 ms/op
                 getUser·p0.99:   3.540 ms/op
                 getUser·p0.999:  13.468 ms/op
                 getUser·p0.9999: 13.646 ms/op
                 getUser·p1.00:   13.681 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16981
  mean =      1.881 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 93 
    [ 1.250,  2.500) = 15264 
    [ 2.500,  3.750) = 1528 
    [ 3.750,  5.000) = 63 
    [ 5.000,  6.250) = 1 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.001 ms/op
     p(50.0000) =      1.706 ms/op
     p(90.0000) =      2.482 ms/op
     p(95.0000) =      2.793 ms/op
     p(99.0000) =      3.540 ms/op
     p(99.9000) =     13.468 ms/op
     p(99.9900) =     13.646 ms/op
     p(99.9990) =     13.681 ms/op
     p(99.9999) =     13.681 ms/op
    p(100.0000) =     13.681 ms/op


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
# Warmup Iteration   1: 4.653 ±(99.9%) 0.131 ms/op
Iteration   1: 3.512 ±(99.9%) 0.038 ms/op
                 listUser·p0.00:   1.018 ms/op
                 listUser·p0.50:   3.301 ms/op
                 listUser·p0.90:   4.538 ms/op
                 listUser·p0.95:   4.784 ms/op
                 listUser·p0.99:   6.930 ms/op
                 listUser·p0.999:  14.680 ms/op
                 listUser·p0.9999: 14.811 ms/op
                 listUser·p1.00:   14.811 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9249
  mean =      3.512 ±(99.9%) 0.038 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 11 
    [ 1.250,  2.500) = 613 
    [ 2.500,  3.750) = 5101 
    [ 3.750,  5.000) = 3253 
    [ 5.000,  6.250) = 156 
    [ 6.250,  7.500) = 42 
    [ 7.500,  8.750) = 24 
    [ 8.750, 10.000) = 16 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.018 ms/op
     p(50.0000) =      3.301 ms/op
     p(90.0000) =      4.538 ms/op
     p(95.0000) =      4.784 ms/op
     p(99.0000) =      6.930 ms/op
     p(99.9000) =     14.680 ms/op
     p(99.9900) =     14.811 ms/op
     p(99.9990) =     14.811 ms/op
     p(99.9999) =     14.811 ms/op
    p(100.0000) =     14.811 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.697          ops/ms
ClientSimple.existUser                       thrpt         13.161          ops/ms
ClientSimple.getUser                         thrpt         11.479          ops/ms
ClientSimple.listUser                        thrpt          8.595          ops/ms
ClientSimple.createUser                       avgt          2.016           ms/op
ClientSimple.existUser                        avgt          2.010           ms/op
ClientSimple.getUser                          avgt          2.107           ms/op
ClientSimple.listUser                         avgt          3.650           ms/op
ClientSimple.createUser                     sample  15288   2.101 ± 0.027   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.634           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.956           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.511           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.002           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.498           ms/op
ClientSimple.createUser:createUser·p0.999   sample         16.550           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         18.022           ms/op
ClientSimple.createUser:createUser·p1.00    sample         18.022           ms/op
ClientSimple.existUser                      sample  15325   2.090 ± 0.034   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.492           ms/op
ClientSimple.existUser:existUser·p0.50      sample          2.036           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.626           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.847           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.751           ms/op
ClientSimple.existUser:existUser·p0.999     sample         23.495           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         23.829           ms/op
ClientSimple.existUser:existUser·p1.00      sample         23.986           ms/op
ClientSimple.getUser                        sample  16981   1.881 ± 0.017   ms/op
ClientSimple.getUser:getUser·p0.00          sample          1.001           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.706           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.482           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.793           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.540           ms/op
ClientSimple.getUser:getUser·p0.999         sample         13.468           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         13.646           ms/op
ClientSimple.getUser:getUser·p1.00          sample         13.681           ms/op
ClientSimple.listUser                       sample   9249   3.512 ± 0.038   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.018           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.301           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.538           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.784           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.930           ms/op
ClientSimple.listUser:listUser·p0.999       sample         14.680           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         14.811           ms/op
ClientSimple.listUser:listUser·p1.00        sample         14.811           ms/op

Benchmark result is saved to 1718844002552.json
