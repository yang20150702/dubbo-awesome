# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 1.732 ops/ms
Iteration   1: 7.630 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.630 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.209 ops/ms
Iteration   1: 13.074 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.074 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 6.222 ops/ms
Iteration   1: 14.318 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  14.318 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 5.246 ops/ms
Iteration   1: 8.186 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.186 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 33.33% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 4.016 ±(99.9%) 0.075 ms/op
Iteration   1: 2.133 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.133 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 41.67% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.106 ±(99.9%) 0.051 ms/op
Iteration   1: 1.904 ±(99.9%) 0.025 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.904 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.194 ±(99.9%) 0.055 ms/op
Iteration   1: 1.839 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.839 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 5.296 ±(99.9%) 0.127 ms/op
Iteration   1: 3.272 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.272 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 3.420 ±(99.9%) 0.092 ms/op
Iteration   1: 2.463 ±(99.9%) 0.105 ms/op
                 createUser·p0.00:   0.646 ms/op
                 createUser·p0.50:   2.105 ms/op
                 createUser·p0.90:   2.896 ms/op
                 createUser·p0.95:   3.105 ms/op
                 createUser·p0.99:   8.094 ms/op
                 createUser·p0.999:  62.722 ms/op
                 createUser·p0.9999: 66.664 ms/op
                 createUser·p1.00:   66.781 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 12979
  mean =      2.463 ±(99.9%) 0.105 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 12828 
    [ 5.000, 10.000) = 35 
    [10.000, 15.000) = 17 
    [15.000, 20.000) = 5 
    [20.000, 25.000) = 18 
    [25.000, 30.000) = 3 
    [30.000, 35.000) = 41 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 0 
    [45.000, 50.000) = 0 
    [50.000, 55.000) = 0 
    [55.000, 60.000) = 0 
    [60.000, 65.000) = 26 

  Percentiles, ms/op:
      p(0.0000) =      0.646 ms/op
     p(50.0000) =      2.105 ms/op
     p(90.0000) =      2.896 ms/op
     p(95.0000) =      3.105 ms/op
     p(99.0000) =      8.094 ms/op
     p(99.9000) =     62.722 ms/op
     p(99.9900) =     66.664 ms/op
     p(99.9990) =     66.781 ms/op
     p(99.9999) =     66.781 ms/op
    p(100.0000) =     66.781 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 75.00% complete, ETA 00:00:20
# Fork: 1 of 1
# Warmup Iteration   1: 2.855 ±(99.9%) 0.070 ms/op
Iteration   1: 2.021 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   0.546 ms/op
                 existUser·p0.50:   2.077 ms/op
                 existUser·p0.90:   2.445 ms/op
                 existUser·p0.95:   2.634 ms/op
                 existUser·p0.99:   3.011 ms/op
                 existUser·p0.999:  12.829 ms/op
                 existUser·p0.9999: 13.647 ms/op
                 existUser·p1.00:   13.713 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15830
  mean =      2.021 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 562 
    [ 1.250,  2.500) = 14005 
    [ 2.500,  3.750) = 1205 
    [ 3.750,  5.000) = 17 
    [ 5.000,  6.250) = 2 
    [ 6.250,  7.500) = 7 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 4 
    [12.500, 13.750) = 28 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.546 ms/op
     p(50.0000) =      2.077 ms/op
     p(90.0000) =      2.445 ms/op
     p(95.0000) =      2.634 ms/op
     p(99.0000) =      3.011 ms/op
     p(99.9000) =     12.829 ms/op
     p(99.9900) =     13.647 ms/op
     p(99.9990) =     13.713 ms/op
     p(99.9999) =     13.713 ms/op
    p(100.0000) =     13.713 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.635 ±(99.9%) 0.131 ms/op
Iteration   1: 2.242 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   0.655 ms/op
                 getUser·p0.50:   2.130 ms/op
                 getUser·p0.90:   2.761 ms/op
                 getUser·p0.95:   2.970 ms/op
                 getUser·p0.99:   4.620 ms/op
                 getUser·p0.999:  16.593 ms/op
                 getUser·p0.9999: 16.770 ms/op
                 getUser·p1.00:   16.777 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14258
  mean =      2.242 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 65 
    [ 1.250,  2.500) = 10869 
    [ 2.500,  3.750) = 3108 
    [ 3.750,  5.000) = 81 
    [ 5.000,  6.250) = 103 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 32 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.655 ms/op
     p(50.0000) =      2.130 ms/op
     p(90.0000) =      2.761 ms/op
     p(95.0000) =      2.970 ms/op
     p(99.0000) =      4.620 ms/op
     p(99.9000) =     16.593 ms/op
     p(99.9900) =     16.770 ms/op
     p(99.9990) =     16.777 ms/op
     p(99.9999) =     16.777 ms/op
    p(100.0000) =     16.777 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.159 ±(99.9%) 0.119 ms/op
Iteration   1: 3.743 ±(99.9%) 0.033 ms/op
                 listUser·p0.00:   0.646 ms/op
                 listUser·p0.50:   3.777 ms/op
                 listUser·p0.90:   4.686 ms/op
                 listUser·p0.95:   4.940 ms/op
                 listUser·p0.99:   6.239 ms/op
                 listUser·p0.999:  11.567 ms/op
                 listUser·p0.9999: 12.829 ms/op
                 listUser·p1.00:   12.829 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8544
  mean =      3.743 ±(99.9%) 0.033 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 11 
    [ 1.250,  2.500) = 463 
    [ 2.500,  3.750) = 3681 
    [ 3.750,  5.000) = 4024 
    [ 5.000,  6.250) = 281 
    [ 6.250,  7.500) = 46 
    [ 7.500,  8.750) = 6 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 7 
    [11.250, 12.500) = 24 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.646 ms/op
     p(50.0000) =      3.777 ms/op
     p(90.0000) =      4.686 ms/op
     p(95.0000) =      4.940 ms/op
     p(99.0000) =      6.239 ms/op
     p(99.9000) =     11.567 ms/op
     p(99.9900) =     12.829 ms/op
     p(99.9990) =     12.829 ms/op
     p(99.9999) =     12.829 ms/op
    p(100.0000) =     12.829 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.630          ops/ms
ClientSimple.existUser                       thrpt         13.074          ops/ms
ClientSimple.getUser                         thrpt         14.318          ops/ms
ClientSimple.listUser                        thrpt          8.186          ops/ms
ClientSimple.createUser                       avgt          2.133           ms/op
ClientSimple.existUser                        avgt          1.904           ms/op
ClientSimple.getUser                          avgt          1.839           ms/op
ClientSimple.listUser                         avgt          3.272           ms/op
ClientSimple.createUser                     sample  12979   2.463 ± 0.105   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.646           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.105           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.896           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.105           ms/op
ClientSimple.createUser:createUser·p0.99    sample          8.094           ms/op
ClientSimple.createUser:createUser·p0.999   sample         62.722           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         66.664           ms/op
ClientSimple.createUser:createUser·p1.00    sample         66.781           ms/op
ClientSimple.existUser                      sample  15830   2.021 ± 0.017   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.546           ms/op
ClientSimple.existUser:existUser·p0.50      sample          2.077           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.445           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.634           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.011           ms/op
ClientSimple.existUser:existUser·p0.999     sample         12.829           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         13.647           ms/op
ClientSimple.existUser:existUser·p1.00      sample         13.713           ms/op
ClientSimple.getUser                        sample  14258   2.242 ± 0.024   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.655           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.130           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.761           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.970           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.620           ms/op
ClientSimple.getUser:getUser·p0.999         sample         16.593           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         16.770           ms/op
ClientSimple.getUser:getUser·p1.00          sample         16.777           ms/op
ClientSimple.listUser                       sample   8544   3.743 ± 0.033   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.646           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.777           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.686           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.940           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.239           ms/op
ClientSimple.listUser:listUser·p0.999       sample         11.567           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         12.829           ms/op
ClientSimple.listUser:listUser·p1.00        sample         12.829           ms/op

Benchmark result is saved to 1712795871591.json
