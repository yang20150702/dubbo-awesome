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
# Warmup Iteration   1: 1.867 ops/ms
Iteration   1: 7.976 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.976 ops/ms


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
# Warmup Iteration   1: 7.199 ops/ms
Iteration   1: 12.628 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.628 ops/ms


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
# Warmup Iteration   1: 5.994 ops/ms
Iteration   1: 13.034 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.034 ops/ms


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
# Warmup Iteration   1: 4.489 ops/ms
Iteration   1: 8.092 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.092 ops/ms


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
# Warmup Iteration   1: 3.929 ±(99.9%) 0.060 ms/op
Iteration   1: 2.279 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.279 ms/op


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
# Warmup Iteration   1: 2.957 ±(99.9%) 0.056 ms/op
Iteration   1: 1.885 ±(99.9%) 0.040 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.885 ms/op


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
# Warmup Iteration   1: 3.260 ±(99.9%) 0.062 ms/op
Iteration   1: 2.380 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.380 ms/op


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
# Warmup Iteration   1: 3.860 ±(99.9%) 0.083 ms/op
Iteration   1: 3.184 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.184 ms/op


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
# Warmup Iteration   1: 3.517 ±(99.9%) 0.082 ms/op
Iteration   1: 2.086 ±(99.9%) 0.030 ms/op
                 createUser·p0.00:   0.324 ms/op
                 createUser·p0.50:   1.870 ms/op
                 createUser·p0.90:   2.666 ms/op
                 createUser·p0.95:   2.843 ms/op
                 createUser·p0.99:   9.421 ms/op
                 createUser·p0.999:  16.100 ms/op
                 createUser·p0.9999: 16.972 ms/op
                 createUser·p1.00:   17.007 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15305
  mean =      2.086 ±(99.9%) 0.030 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 453 
    [ 1.250,  2.500) = 12272 
    [ 2.500,  3.750) = 2280 
    [ 3.750,  5.000) = 82 
    [ 5.000,  6.250) = 13 
    [ 6.250,  7.500) = 44 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 72 
    [10.000, 11.250) = 56 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 21 
    [16.250, 17.500) = 11 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.324 ms/op
     p(50.0000) =      1.870 ms/op
     p(90.0000) =      2.666 ms/op
     p(95.0000) =      2.843 ms/op
     p(99.0000) =      9.421 ms/op
     p(99.9000) =     16.100 ms/op
     p(99.9900) =     16.972 ms/op
     p(99.9990) =     17.007 ms/op
     p(99.9999) =     17.007 ms/op
    p(100.0000) =     17.007 ms/op


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
# Warmup Iteration   1: 2.848 ±(99.9%) 0.059 ms/op
Iteration   1: 1.984 ±(99.9%) 0.027 ms/op
                 existUser·p0.00:   0.606 ms/op
                 existUser·p0.50:   1.913 ms/op
                 existUser·p0.90:   2.376 ms/op
                 existUser·p0.95:   2.621 ms/op
                 existUser·p0.99:   4.390 ms/op
                 existUser·p0.999:  20.273 ms/op
                 existUser·p0.9999: 20.853 ms/op
                 existUser·p1.00:   20.873 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16306
  mean =      1.984 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15169 
    [ 2.500,  5.000) = 991 
    [ 5.000,  7.500) = 82 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 7 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.606 ms/op
     p(50.0000) =      1.913 ms/op
     p(90.0000) =      2.376 ms/op
     p(95.0000) =      2.621 ms/op
     p(99.0000) =      4.390 ms/op
     p(99.9000) =     20.273 ms/op
     p(99.9900) =     20.853 ms/op
     p(99.9990) =     20.873 ms/op
     p(99.9999) =     20.873 ms/op
    p(100.0000) =     20.873 ms/op


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
# Warmup Iteration   1: 3.237 ±(99.9%) 0.075 ms/op
Iteration   1: 1.941 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   0.539 ms/op
                 getUser·p0.50:   1.896 ms/op
                 getUser·p0.90:   2.355 ms/op
                 getUser·p0.95:   2.488 ms/op
                 getUser·p0.99:   3.219 ms/op
                 getUser·p0.999:  11.289 ms/op
                 getUser·p0.9999: 12.026 ms/op
                 getUser·p1.00:   12.386 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16470
  mean =      1.941 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 323 
    [ 1.250,  2.500) = 15356 
    [ 2.500,  3.750) = 689 
    [ 3.750,  5.000) = 48 
    [ 5.000,  6.250) = 21 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 11 
    [11.250, 12.500) = 21 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.539 ms/op
     p(50.0000) =      1.896 ms/op
     p(90.0000) =      2.355 ms/op
     p(95.0000) =      2.488 ms/op
     p(99.0000) =      3.219 ms/op
     p(99.9000) =     11.289 ms/op
     p(99.9900) =     12.026 ms/op
     p(99.9990) =     12.386 ms/op
     p(99.9999) =     12.386 ms/op
    p(100.0000) =     12.386 ms/op


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
# Warmup Iteration   1: 4.244 ±(99.9%) 0.126 ms/op
Iteration   1: 3.350 ±(99.9%) 0.029 ms/op
                 listUser·p0.00:   1.356 ms/op
                 listUser·p0.50:   3.334 ms/op
                 listUser·p0.90:   4.252 ms/op
                 listUser·p0.95:   4.604 ms/op
                 listUser·p0.99:   6.915 ms/op
                 listUser·p0.999:  8.096 ms/op
                 listUser·p0.9999: 8.184 ms/op
                 listUser·p1.00:   8.184 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9556
  mean =      3.350 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [1.000, 1.500) = 4 
    [1.500, 2.000) = 101 
    [2.000, 2.500) = 1026 
    [2.500, 3.000) = 2584 
    [3.000, 3.500) = 2082 
    [3.500, 4.000) = 2097 
    [4.000, 4.500) = 1083 
    [4.500, 5.000) = 297 
    [5.000, 5.500) = 98 
    [5.500, 6.000) = 30 
    [6.000, 6.500) = 16 
    [6.500, 7.000) = 49 
    [7.000, 7.500) = 50 
    [7.500, 8.000) = 23 
    [8.000, 8.500) = 16 

  Percentiles, ms/op:
      p(0.0000) =      1.356 ms/op
     p(50.0000) =      3.334 ms/op
     p(90.0000) =      4.252 ms/op
     p(95.0000) =      4.604 ms/op
     p(99.0000) =      6.915 ms/op
     p(99.9000) =      8.096 ms/op
     p(99.9900) =      8.184 ms/op
     p(99.9990) =      8.184 ms/op
     p(99.9999) =      8.184 ms/op
    p(100.0000) =      8.184 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.976          ops/ms
ClientSimple.existUser                       thrpt         12.628          ops/ms
ClientSimple.getUser                         thrpt         13.034          ops/ms
ClientSimple.listUser                        thrpt          8.092          ops/ms
ClientSimple.createUser                       avgt          2.279           ms/op
ClientSimple.existUser                        avgt          1.885           ms/op
ClientSimple.getUser                          avgt          2.380           ms/op
ClientSimple.listUser                         avgt          3.184           ms/op
ClientSimple.createUser                     sample  15305   2.086 ± 0.030   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.324           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.870           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.666           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.843           ms/op
ClientSimple.createUser:createUser·p0.99    sample          9.421           ms/op
ClientSimple.createUser:createUser·p0.999   sample         16.100           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         16.972           ms/op
ClientSimple.createUser:createUser·p1.00    sample         17.007           ms/op
ClientSimple.existUser                      sample  16306   1.984 ± 0.027   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.606           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.913           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.376           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.621           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.390           ms/op
ClientSimple.existUser:existUser·p0.999     sample         20.273           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         20.853           ms/op
ClientSimple.existUser:existUser·p1.00      sample         20.873           ms/op
ClientSimple.getUser                        sample  16470   1.941 ± 0.015   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.539           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.896           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.355           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.488           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.219           ms/op
ClientSimple.getUser:getUser·p0.999         sample         11.289           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         12.026           ms/op
ClientSimple.getUser:getUser·p1.00          sample         12.386           ms/op
ClientSimple.listUser                       sample   9556   3.350 ± 0.029   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.356           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.334           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.252           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.604           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.915           ms/op
ClientSimple.listUser:listUser·p0.999       sample          8.096           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          8.184           ms/op
ClientSimple.listUser:listUser·p1.00        sample          8.184           ms/op

Benchmark result is saved to 1715301522960.json
