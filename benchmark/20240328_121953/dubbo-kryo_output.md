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
# Warmup Iteration   1: 1.517 ops/ms
Iteration   1: 6.533 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.533 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 6.494 ops/ms
Iteration   1: 13.298 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.298 ops/ms


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
# Warmup Iteration   1: 5.226 ops/ms
Iteration   1: 11.985 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.985 ops/ms


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
# Warmup Iteration   1: 5.318 ops/ms
Iteration   1: 7.923 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  7.923 ops/ms


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
# Warmup Iteration   1: 4.106 ±(99.9%) 0.075 ms/op
Iteration   1: 2.029 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.029 ms/op


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
# Warmup Iteration   1: 3.408 ±(99.9%) 0.062 ms/op
Iteration   1: 2.008 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.008 ms/op


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
# Warmup Iteration   1: 3.834 ±(99.9%) 0.071 ms/op
Iteration   1: 2.175 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.175 ms/op


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
# Warmup Iteration   1: 5.023 ±(99.9%) 0.133 ms/op
Iteration   1: 3.459 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.459 ms/op


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
# Warmup Iteration   1: 3.618 ±(99.9%) 0.098 ms/op
Iteration   1: 2.396 ±(99.9%) 0.031 ms/op
                 createUser·p0.00:   0.693 ms/op
                 createUser·p0.50:   2.298 ms/op
                 createUser·p0.90:   3.006 ms/op
                 createUser·p0.95:   3.389 ms/op
                 createUser·p0.99:   7.311 ms/op
                 createUser·p0.999:  14.347 ms/op
                 createUser·p0.9999: 14.904 ms/op
                 createUser·p1.00:   14.909 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13349
  mean =      2.396 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 86 
    [ 1.250,  2.500) = 8676 
    [ 2.500,  3.750) = 4175 
    [ 3.750,  5.000) = 188 
    [ 5.000,  6.250) = 55 
    [ 6.250,  7.500) = 60 
    [ 7.500,  8.750) = 13 
    [ 8.750, 10.000) = 31 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 31 
    [12.500, 13.750) = 4 
    [13.750, 15.000) = 29 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.693 ms/op
     p(50.0000) =      2.298 ms/op
     p(90.0000) =      3.006 ms/op
     p(95.0000) =      3.389 ms/op
     p(99.0000) =      7.311 ms/op
     p(99.9000) =     14.347 ms/op
     p(99.9900) =     14.904 ms/op
     p(99.9990) =     14.909 ms/op
     p(99.9999) =     14.909 ms/op
    p(100.0000) =     14.909 ms/op


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
# Warmup Iteration   1: 3.177 ±(99.9%) 0.072 ms/op
Iteration   1: 2.033 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   0.534 ms/op
                 existUser·p0.50:   2.001 ms/op
                 existUser·p0.90:   2.671 ms/op
                 existUser·p0.95:   2.839 ms/op
                 existUser·p0.99:   3.596 ms/op
                 existUser·p0.999:  12.738 ms/op
                 existUser·p0.9999: 13.156 ms/op
                 existUser·p1.00:   13.156 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15853
  mean =      2.033 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 547 
    [ 1.250,  2.500) = 12294 
    [ 2.500,  3.750) = 2875 
    [ 3.750,  5.000) = 75 
    [ 5.000,  6.250) = 29 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 7 
    [12.500, 13.750) = 24 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.534 ms/op
     p(50.0000) =      2.001 ms/op
     p(90.0000) =      2.671 ms/op
     p(95.0000) =      2.839 ms/op
     p(99.0000) =      3.596 ms/op
     p(99.9000) =     12.738 ms/op
     p(99.9900) =     13.156 ms/op
     p(99.9990) =     13.156 ms/op
     p(99.9999) =     13.156 ms/op
    p(100.0000) =     13.156 ms/op


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
# Warmup Iteration   1: 3.583 ±(99.9%) 0.109 ms/op
Iteration   1: 2.272 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   0.334 ms/op
                 getUser·p0.50:   2.167 ms/op
                 getUser·p0.90:   2.994 ms/op
                 getUser·p0.95:   3.222 ms/op
                 getUser·p0.99:   3.782 ms/op
                 getUser·p0.999:  12.298 ms/op
                 getUser·p0.9999: 13.071 ms/op
                 getUser·p1.00:   13.091 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14069
  mean =      2.272 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 129 
    [ 1.250,  2.500) = 9294 
    [ 2.500,  3.750) = 4485 
    [ 3.750,  5.000) = 126 
    [ 5.000,  6.250) = 2 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 2 
    [11.250, 12.500) = 27 
    [12.500, 13.750) = 3 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.334 ms/op
     p(50.0000) =      2.167 ms/op
     p(90.0000) =      2.994 ms/op
     p(95.0000) =      3.222 ms/op
     p(99.0000) =      3.782 ms/op
     p(99.9000) =     12.298 ms/op
     p(99.9900) =     13.071 ms/op
     p(99.9990) =     13.091 ms/op
     p(99.9999) =     13.091 ms/op
    p(100.0000) =     13.091 ms/op


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
# Warmup Iteration   1: 4.490 ±(99.9%) 0.135 ms/op
Iteration   1: 3.379 ±(99.9%) 0.039 ms/op
                 listUser·p0.00:   1.221 ms/op
                 listUser·p0.50:   3.133 ms/op
                 listUser·p0.90:   4.196 ms/op
                 listUser·p0.95:   4.489 ms/op
                 listUser·p0.99:   6.339 ms/op
                 listUser·p0.999:  18.153 ms/op
                 listUser·p0.9999: 18.547 ms/op
                 listUser·p1.00:   18.547 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9457
  mean =      3.379 ±(99.9%) 0.039 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1 
    [ 1.250,  2.500) = 473 
    [ 2.500,  3.750) = 6563 
    [ 3.750,  5.000) = 2193 
    [ 5.000,  6.250) = 132 
    [ 6.250,  7.500) = 31 
    [ 7.500,  8.750) = 32 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 32 

  Percentiles, ms/op:
      p(0.0000) =      1.221 ms/op
     p(50.0000) =      3.133 ms/op
     p(90.0000) =      4.196 ms/op
     p(95.0000) =      4.489 ms/op
     p(99.0000) =      6.339 ms/op
     p(99.9000) =     18.153 ms/op
     p(99.9900) =     18.547 ms/op
     p(99.9990) =     18.547 ms/op
     p(99.9999) =     18.547 ms/op
    p(100.0000) =     18.547 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.533          ops/ms
ClientSimple.existUser                       thrpt         13.298          ops/ms
ClientSimple.getUser                         thrpt         11.985          ops/ms
ClientSimple.listUser                        thrpt          7.923          ops/ms
ClientSimple.createUser                       avgt          2.029           ms/op
ClientSimple.existUser                        avgt          2.008           ms/op
ClientSimple.getUser                          avgt          2.175           ms/op
ClientSimple.listUser                         avgt          3.459           ms/op
ClientSimple.createUser                     sample  13349   2.396 ± 0.031   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.693           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.298           ms/op
ClientSimple.createUser:createUser·p0.90    sample          3.006           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.389           ms/op
ClientSimple.createUser:createUser·p0.99    sample          7.311           ms/op
ClientSimple.createUser:createUser·p0.999   sample         14.347           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         14.904           ms/op
ClientSimple.createUser:createUser·p1.00    sample         14.909           ms/op
ClientSimple.existUser                      sample  15853   2.033 ± 0.019   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.534           ms/op
ClientSimple.existUser:existUser·p0.50      sample          2.001           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.671           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.839           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.596           ms/op
ClientSimple.existUser:existUser·p0.999     sample         12.738           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         13.156           ms/op
ClientSimple.existUser:existUser·p1.00      sample         13.156           ms/op
ClientSimple.getUser                        sample  14069   2.272 ± 0.020   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.334           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.167           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.994           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.222           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.782           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.298           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         13.071           ms/op
ClientSimple.getUser:getUser·p1.00          sample         13.091           ms/op
ClientSimple.listUser                       sample   9457   3.379 ± 0.039   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.221           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.133           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.196           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.489           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.339           ms/op
ClientSimple.listUser:listUser·p0.999       sample         18.153           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         18.547           ms/op
ClientSimple.listUser:listUser·p1.00        sample         18.547           ms/op

Benchmark result is saved to 1711628161241.json
