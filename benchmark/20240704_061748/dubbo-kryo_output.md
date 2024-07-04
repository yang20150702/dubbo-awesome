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
# Warmup Iteration   1: 1.606 ops/ms
Iteration   1: 6.647 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.647 ops/ms


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
# Warmup Iteration   1: 5.513 ops/ms
Iteration   1: 13.457 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.457 ops/ms


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
# Warmup Iteration   1: 5.061 ops/ms
Iteration   1: 11.652 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.652 ops/ms


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
# Warmup Iteration   1: 4.492 ops/ms
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
# Warmup Iteration   1: 4.056 ±(99.9%) 0.114 ms/op
Iteration   1: 2.143 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.143 ms/op


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
# Warmup Iteration   1: 3.195 ±(99.9%) 0.058 ms/op
Iteration   1: 2.005 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.005 ms/op


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
# Warmup Iteration   1: 3.716 ±(99.9%) 0.075 ms/op
Iteration   1: 2.067 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.067 ms/op


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
# Warmup Iteration   1: 4.414 ±(99.9%) 0.088 ms/op
Iteration   1: 3.331 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.331 ms/op


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
# Warmup Iteration   1: 3.361 ±(99.9%) 0.103 ms/op
Iteration   1: 2.344 ±(99.9%) 0.040 ms/op
                 createUser·p0.00:   0.638 ms/op
                 createUser·p0.50:   2.265 ms/op
                 createUser·p0.90:   2.806 ms/op
                 createUser·p0.95:   3.060 ms/op
                 createUser·p0.99:   4.795 ms/op
                 createUser·p0.999:  28.674 ms/op
                 createUser·p0.9999: 29.479 ms/op
                 createUser·p1.00:   29.491 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13642
  mean =      2.344 ±(99.9%) 0.040 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9958 
    [ 2.500,  5.000) = 3549 
    [ 5.000,  7.500) = 103 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.638 ms/op
     p(50.0000) =      2.265 ms/op
     p(90.0000) =      2.806 ms/op
     p(95.0000) =      3.060 ms/op
     p(99.0000) =      4.795 ms/op
     p(99.9000) =     28.674 ms/op
     p(99.9900) =     29.479 ms/op
     p(99.9990) =     29.491 ms/op
     p(99.9999) =     29.491 ms/op
    p(100.0000) =     29.491 ms/op


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
# Warmup Iteration   1: 3.054 ±(99.9%) 0.079 ms/op
Iteration   1: 1.711 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   0.840 ms/op
                 existUser·p0.50:   1.622 ms/op
                 existUser·p0.90:   2.030 ms/op
                 existUser·p0.95:   2.265 ms/op
                 existUser·p0.99:   3.123 ms/op
                 existUser·p0.999:  13.517 ms/op
                 existUser·p0.9999: 14.744 ms/op
                 existUser·p1.00:   14.844 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 18746
  mean =      1.711 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 622 
    [ 1.250,  2.500) = 17669 
    [ 2.500,  3.750) = 332 
    [ 3.750,  5.000) = 32 
    [ 5.000,  6.250) = 18 
    [ 6.250,  7.500) = 7 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 51 
    [13.750, 15.000) = 12 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.840 ms/op
     p(50.0000) =      1.622 ms/op
     p(90.0000) =      2.030 ms/op
     p(95.0000) =      2.265 ms/op
     p(99.0000) =      3.123 ms/op
     p(99.9000) =     13.517 ms/op
     p(99.9900) =     14.744 ms/op
     p(99.9990) =     14.844 ms/op
     p(99.9999) =     14.844 ms/op
    p(100.0000) =     14.844 ms/op


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
# Warmup Iteration   1: 3.830 ±(99.9%) 0.200 ms/op
Iteration   1: 2.122 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   0.733 ms/op
                 getUser·p0.50:   2.005 ms/op
                 getUser·p0.90:   2.560 ms/op
                 getUser·p0.95:   2.826 ms/op
                 getUser·p0.99:   3.716 ms/op
                 getUser·p0.999:  14.811 ms/op
                 getUser·p0.9999: 14.917 ms/op
                 getUser·p1.00:   14.926 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15192
  mean =      2.122 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 120 
    [ 1.250,  2.500) = 13296 
    [ 2.500,  3.750) = 1634 
    [ 3.750,  5.000) = 39 
    [ 5.000,  6.250) = 41 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 16 
    [ 8.750, 10.000) = 13 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.733 ms/op
     p(50.0000) =      2.005 ms/op
     p(90.0000) =      2.560 ms/op
     p(95.0000) =      2.826 ms/op
     p(99.0000) =      3.716 ms/op
     p(99.9000) =     14.811 ms/op
     p(99.9900) =     14.917 ms/op
     p(99.9990) =     14.926 ms/op
     p(99.9999) =     14.926 ms/op
    p(100.0000) =     14.926 ms/op


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
# Warmup Iteration   1: 4.777 ±(99.9%) 0.185 ms/op
Iteration   1: 3.757 ±(99.9%) 0.100 ms/op
                 listUser·p0.00:   1.145 ms/op
                 listUser·p0.50:   3.514 ms/op
                 listUser·p0.90:   4.645 ms/op
                 listUser·p0.95:   5.104 ms/op
                 listUser·p0.99:   10.151 ms/op
                 listUser·p0.999:  39.942 ms/op
                 listUser·p0.9999: 40.632 ms/op
                 listUser·p1.00:   40.632 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8536
  mean =      3.757 ±(99.9%) 0.100 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 8048 
    [ 5.000, 10.000) = 402 
    [10.000, 15.000) = 21 
    [15.000, 20.000) = 3 
    [20.000, 25.000) = 2 
    [25.000, 30.000) = 24 
    [30.000, 35.000) = 4 
    [35.000, 40.000) = 27 
    [40.000, 45.000) = 5 

  Percentiles, ms/op:
      p(0.0000) =      1.145 ms/op
     p(50.0000) =      3.514 ms/op
     p(90.0000) =      4.645 ms/op
     p(95.0000) =      5.104 ms/op
     p(99.0000) =     10.151 ms/op
     p(99.9000) =     39.942 ms/op
     p(99.9900) =     40.632 ms/op
     p(99.9990) =     40.632 ms/op
     p(99.9999) =     40.632 ms/op
    p(100.0000) =     40.632 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.647          ops/ms
ClientSimple.existUser                       thrpt         13.457          ops/ms
ClientSimple.getUser                         thrpt         11.652          ops/ms
ClientSimple.listUser                        thrpt          8.130          ops/ms
ClientSimple.createUser                       avgt          2.143           ms/op
ClientSimple.existUser                        avgt          2.005           ms/op
ClientSimple.getUser                          avgt          2.067           ms/op
ClientSimple.listUser                         avgt          3.331           ms/op
ClientSimple.createUser                     sample  13642   2.344 ± 0.040   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.638           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.265           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.806           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.060           ms/op
ClientSimple.createUser:createUser·p0.99    sample          4.795           ms/op
ClientSimple.createUser:createUser·p0.999   sample         28.674           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         29.479           ms/op
ClientSimple.createUser:createUser·p1.00    sample         29.491           ms/op
ClientSimple.existUser                      sample  18746   1.711 ± 0.018   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.840           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.622           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.030           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.265           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.123           ms/op
ClientSimple.existUser:existUser·p0.999     sample         13.517           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         14.744           ms/op
ClientSimple.existUser:existUser·p1.00      sample         14.844           ms/op
ClientSimple.getUser                        sample  15192   2.122 ± 0.021   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.733           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.005           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.560           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.826           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.716           ms/op
ClientSimple.getUser:getUser·p0.999         sample         14.811           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         14.917           ms/op
ClientSimple.getUser:getUser·p1.00          sample         14.926           ms/op
ClientSimple.listUser                       sample   8536   3.757 ± 0.100   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.145           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.514           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.645           ms/op
ClientSimple.listUser:listUser·p0.95        sample          5.104           ms/op
ClientSimple.listUser:listUser·p0.99        sample         10.151           ms/op
ClientSimple.listUser:listUser·p0.999       sample         39.942           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         40.632           ms/op
ClientSimple.listUser:listUser·p1.00        sample         40.632           ms/op

Benchmark result is saved to 1720073622631.json
