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
# Warmup Iteration   1: 1.689 ops/ms
Iteration   1: 6.767 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.767 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:19
# Fork: 1 of 1
# Warmup Iteration   1: 6.397 ops/ms
Iteration   1: 12.471 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.471 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:11
# Fork: 1 of 1
# Warmup Iteration   1: 6.322 ops/ms
Iteration   1: 12.644 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.644 ops/ms


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
# Warmup Iteration   1: 6.067 ops/ms
Iteration   1: 8.387 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.387 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 4.834 ±(99.9%) 0.098 ms/op
Iteration   1: 2.228 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.228 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.382 ±(99.9%) 0.048 ms/op
Iteration   1: 2.031 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.031 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 3.256 ±(99.9%) 0.102 ms/op
Iteration   1: 1.820 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.820 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 5.002 ±(99.9%) 0.147 ms/op
Iteration   1: 3.300 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.300 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.724 ±(99.9%) 0.146 ms/op
Iteration   1: 2.400 ±(99.9%) 0.033 ms/op
                 createUser·p0.00:   0.844 ms/op
                 createUser·p0.50:   2.245 ms/op
                 createUser·p0.90:   2.802 ms/op
                 createUser·p0.95:   3.170 ms/op
                 createUser·p0.99:   9.156 ms/op
                 createUser·p0.999:  14.812 ms/op
                 createUser·p0.9999: 16.220 ms/op
                 createUser·p1.00:   16.237 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13313
  mean =      2.400 ±(99.9%) 0.033 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 48 
    [ 1.250,  2.500) = 10087 
    [ 2.500,  3.750) = 2794 
    [ 3.750,  5.000) = 156 
    [ 5.000,  6.250) = 34 
    [ 6.250,  7.500) = 34 
    [ 7.500,  8.750) = 14 
    [ 8.750, 10.000) = 52 
    [10.000, 11.250) = 5 
    [11.250, 12.500) = 57 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 27 
    [15.000, 16.250) = 5 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.844 ms/op
     p(50.0000) =      2.245 ms/op
     p(90.0000) =      2.802 ms/op
     p(95.0000) =      3.170 ms/op
     p(99.0000) =      9.156 ms/op
     p(99.9000) =     14.812 ms/op
     p(99.9900) =     16.220 ms/op
     p(99.9990) =     16.237 ms/op
     p(99.9999) =     16.237 ms/op
    p(100.0000) =     16.237 ms/op


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

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 3.187 ±(99.9%) 0.100 ms/op
Iteration   1: 1.800 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   0.691 ms/op
                 existUser·p0.50:   1.647 ms/op
                 existUser·p0.90:   2.396 ms/op
                 existUser·p0.95:   2.560 ms/op
                 existUser·p0.99:   2.938 ms/op
                 existUser·p0.999:  12.374 ms/op
                 existUser·p0.9999: 13.107 ms/op
                 existUser·p1.00:   13.107 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17779
  mean =      1.800 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 822 
    [ 1.250,  2.500) = 15777 
    [ 2.500,  3.750) = 1072 
    [ 3.750,  5.000) = 47 
    [ 5.000,  6.250) = 17 
    [ 6.250,  7.500) = 12 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 19 
    [12.500, 13.750) = 13 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.691 ms/op
     p(50.0000) =      1.647 ms/op
     p(90.0000) =      2.396 ms/op
     p(95.0000) =      2.560 ms/op
     p(99.0000) =      2.938 ms/op
     p(99.9000) =     12.374 ms/op
     p(99.9900) =     13.107 ms/op
     p(99.9990) =     13.107 ms/op
     p(99.9999) =     13.107 ms/op
    p(100.0000) =     13.107 ms/op


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
# Warmup Iteration   1: 3.293 ±(99.9%) 0.098 ms/op
Iteration   1: 2.010 ±(99.9%) 0.033 ms/op
                 getUser·p0.00:   0.751 ms/op
                 getUser·p0.50:   1.919 ms/op
                 getUser·p0.90:   2.400 ms/op
                 getUser·p0.95:   2.670 ms/op
                 getUser·p0.99:   5.005 ms/op
                 getUser·p0.999:  22.774 ms/op
                 getUser·p0.9999: 22.866 ms/op
                 getUser·p1.00:   22.905 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15900
  mean =      2.010 ±(99.9%) 0.033 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14747 
    [ 2.500,  5.000) = 994 
    [ 5.000,  7.500) = 57 
    [ 7.500, 10.000) = 19 
    [10.000, 12.500) = 19 
    [12.500, 15.000) = 24 
    [15.000, 17.500) = 8 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.751 ms/op
     p(50.0000) =      1.919 ms/op
     p(90.0000) =      2.400 ms/op
     p(95.0000) =      2.670 ms/op
     p(99.0000) =      5.005 ms/op
     p(99.9000) =     22.774 ms/op
     p(99.9900) =     22.866 ms/op
     p(99.9990) =     22.905 ms/op
     p(99.9999) =     22.905 ms/op
    p(100.0000) =     22.905 ms/op


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
# Warmup Iteration   1: 4.511 ±(99.9%) 0.123 ms/op
Iteration   1: 3.234 ±(99.9%) 0.031 ms/op
                 listUser·p0.00:   0.732 ms/op
                 listUser·p0.50:   3.088 ms/op
                 listUser·p0.90:   4.116 ms/op
                 listUser·p0.95:   4.481 ms/op
                 listUser·p0.99:   6.947 ms/op
                 listUser·p0.999:  11.403 ms/op
                 listUser·p0.9999: 11.567 ms/op
                 listUser·p1.00:   11.567 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9963
  mean =      3.234 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 5 
    [ 1.250,  2.500) = 1929 
    [ 2.500,  3.750) = 5798 
    [ 3.750,  5.000) = 1999 
    [ 5.000,  6.250) = 109 
    [ 6.250,  7.500) = 76 
    [ 7.500,  8.750) = 15 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 13 
    [11.250, 12.500) = 19 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.732 ms/op
     p(50.0000) =      3.088 ms/op
     p(90.0000) =      4.116 ms/op
     p(95.0000) =      4.481 ms/op
     p(99.0000) =      6.947 ms/op
     p(99.9000) =     11.403 ms/op
     p(99.9900) =     11.567 ms/op
     p(99.9990) =     11.567 ms/op
     p(99.9999) =     11.567 ms/op
    p(100.0000) =     11.567 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.767          ops/ms
ClientSimple.existUser                       thrpt         12.471          ops/ms
ClientSimple.getUser                         thrpt         12.644          ops/ms
ClientSimple.listUser                        thrpt          8.387          ops/ms
ClientSimple.createUser                       avgt          2.228           ms/op
ClientSimple.existUser                        avgt          2.031           ms/op
ClientSimple.getUser                          avgt          1.820           ms/op
ClientSimple.listUser                         avgt          3.300           ms/op
ClientSimple.createUser                     sample  13313   2.400 ± 0.033   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.844           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.245           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.802           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.170           ms/op
ClientSimple.createUser:createUser·p0.99    sample          9.156           ms/op
ClientSimple.createUser:createUser·p0.999   sample         14.812           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         16.220           ms/op
ClientSimple.createUser:createUser·p1.00    sample         16.237           ms/op
ClientSimple.existUser                      sample  17779   1.800 ± 0.016   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.691           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.647           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.396           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.560           ms/op
ClientSimple.existUser:existUser·p0.99      sample          2.938           ms/op
ClientSimple.existUser:existUser·p0.999     sample         12.374           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         13.107           ms/op
ClientSimple.existUser:existUser·p1.00      sample         13.107           ms/op
ClientSimple.getUser                        sample  15900   2.010 ± 0.033   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.751           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.919           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.400           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.670           ms/op
ClientSimple.getUser:getUser·p0.99          sample          5.005           ms/op
ClientSimple.getUser:getUser·p0.999         sample         22.774           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         22.866           ms/op
ClientSimple.getUser:getUser·p1.00          sample         22.905           ms/op
ClientSimple.listUser                       sample   9963   3.234 ± 0.031   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.732           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.088           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.116           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.481           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.947           ms/op
ClientSimple.listUser:listUser·p0.999       sample         11.403           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         11.567           ms/op
ClientSimple.listUser:listUser·p1.00        sample         11.567           ms/op

Benchmark result is saved to 1712211076587.json
