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
# Warmup Iteration   1: 1.847 ops/ms
Iteration   1: 6.933 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.933 ops/ms


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
# Warmup Iteration   1: 6.641 ops/ms
Iteration   1: 13.929 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.929 ops/ms


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
# Warmup Iteration   1: 5.056 ops/ms
Iteration   1: 13.092 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.092 ops/ms


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
# Warmup Iteration   1: 5.652 ops/ms
Iteration   1: 8.587 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.587 ops/ms


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
# Warmup Iteration   1: 3.806 ±(99.9%) 0.071 ms/op
Iteration   1: 2.207 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.207 ms/op


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
# Warmup Iteration   1: 3.182 ±(99.9%) 0.050 ms/op
Iteration   1: 1.962 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.962 ms/op


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
# Warmup Iteration   1: 3.412 ±(99.9%) 0.075 ms/op
Iteration   1: 1.992 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.992 ms/op


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
# Warmup Iteration   1: 4.361 ±(99.9%) 0.106 ms/op
Iteration   1: 3.751 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.751 ms/op


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
# Warmup Iteration   1: 3.519 ±(99.9%) 0.096 ms/op
Iteration   1: 2.110 ±(99.9%) 0.036 ms/op
                 createUser·p0.00:   0.504 ms/op
                 createUser·p0.50:   2.015 ms/op
                 createUser·p0.90:   2.540 ms/op
                 createUser·p0.95:   2.757 ms/op
                 createUser·p0.99:   4.243 ms/op
                 createUser·p0.999:  28.305 ms/op
                 createUser·p0.9999: 32.526 ms/op
                 createUser·p1.00:   34.472 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15209
  mean =      2.110 ±(99.9%) 0.036 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13523 
    [ 2.500,  5.000) = 1576 
    [ 5.000,  7.500) = 65 
    [ 7.500, 10.000) = 13 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 23 
    [30.000, 32.500) = 8 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.504 ms/op
     p(50.0000) =      2.015 ms/op
     p(90.0000) =      2.540 ms/op
     p(95.0000) =      2.757 ms/op
     p(99.0000) =      4.243 ms/op
     p(99.9000) =     28.305 ms/op
     p(99.9900) =     32.526 ms/op
     p(99.9990) =     34.472 ms/op
     p(99.9999) =     34.472 ms/op
    p(100.0000) =     34.472 ms/op


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
# Warmup Iteration   1: 2.957 ±(99.9%) 0.068 ms/op
Iteration   1: 1.708 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.422 ms/op
                 existUser·p0.50:   1.683 ms/op
                 existUser·p0.90:   1.880 ms/op
                 existUser·p0.95:   1.987 ms/op
                 existUser·p0.99:   2.577 ms/op
                 existUser·p0.999:  5.794 ms/op
                 existUser·p0.9999: 6.738 ms/op
                 existUser·p1.00:   8.249 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 18742
  mean =      1.708 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 1 
    [0.500, 1.000) = 32 
    [1.000, 1.500) = 1751 
    [1.500, 2.000) = 16096 
    [2.000, 2.500) = 654 
    [2.500, 3.000) = 96 
    [3.000, 3.500) = 8 
    [3.500, 4.000) = 11 
    [4.000, 4.500) = 30 
    [4.500, 5.000) = 32 
    [5.000, 5.500) = 1 
    [5.500, 6.000) = 27 
    [6.000, 6.500) = 0 
    [6.500, 7.000) = 2 
    [7.000, 7.500) = 0 
    [7.500, 8.000) = 0 
    [8.000, 8.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.422 ms/op
     p(50.0000) =      1.683 ms/op
     p(90.0000) =      1.880 ms/op
     p(95.0000) =      1.987 ms/op
     p(99.0000) =      2.577 ms/op
     p(99.9000) =      5.794 ms/op
     p(99.9900) =      6.738 ms/op
     p(99.9990) =      8.249 ms/op
     p(99.9999) =      8.249 ms/op
    p(100.0000) =      8.249 ms/op


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
# Warmup Iteration   1: 3.246 ±(99.9%) 0.073 ms/op
Iteration   1: 2.384 ±(99.9%) 0.026 ms/op
                 getUser·p0.00:   0.783 ms/op
                 getUser·p0.50:   2.269 ms/op
                 getUser·p0.90:   2.994 ms/op
                 getUser·p0.95:   3.187 ms/op
                 getUser·p0.99:   4.260 ms/op
                 getUser·p0.999:  17.413 ms/op
                 getUser·p0.9999: 17.976 ms/op
                 getUser·p1.00:   18.022 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 13518
  mean =      2.384 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 149 
    [ 1.250,  2.500) = 8692 
    [ 2.500,  3.750) = 4435 
    [ 3.750,  5.000) = 146 
    [ 5.000,  6.250) = 64 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 6 
    [16.250, 17.500) = 15 
    [17.500, 18.750) = 11 

  Percentiles, ms/op:
      p(0.0000) =      0.783 ms/op
     p(50.0000) =      2.269 ms/op
     p(90.0000) =      2.994 ms/op
     p(95.0000) =      3.187 ms/op
     p(99.0000) =      4.260 ms/op
     p(99.9000) =     17.413 ms/op
     p(99.9900) =     17.976 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 5.449 ±(99.9%) 0.151 ms/op
Iteration   1: 3.564 ±(99.9%) 0.035 ms/op
                 listUser·p0.00:   1.417 ms/op
                 listUser·p0.50:   3.531 ms/op
                 listUser·p0.90:   4.317 ms/op
                 listUser·p0.95:   4.932 ms/op
                 listUser·p0.99:   6.098 ms/op
                 listUser·p0.999:  14.762 ms/op
                 listUser·p0.9999: 15.712 ms/op
                 listUser·p1.00:   15.712 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8981
  mean =      3.564 ±(99.9%) 0.035 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 666 
    [ 2.500,  3.750) = 5223 
    [ 3.750,  5.000) = 2668 
    [ 5.000,  6.250) = 352 
    [ 6.250,  7.500) = 39 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 31 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.417 ms/op
     p(50.0000) =      3.531 ms/op
     p(90.0000) =      4.317 ms/op
     p(95.0000) =      4.932 ms/op
     p(99.0000) =      6.098 ms/op
     p(99.9000) =     14.762 ms/op
     p(99.9900) =     15.712 ms/op
     p(99.9990) =     15.712 ms/op
     p(99.9999) =     15.712 ms/op
    p(100.0000) =     15.712 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.933          ops/ms
ClientSimple.existUser                       thrpt         13.929          ops/ms
ClientSimple.getUser                         thrpt         13.092          ops/ms
ClientSimple.listUser                        thrpt          8.587          ops/ms
ClientSimple.createUser                       avgt          2.207           ms/op
ClientSimple.existUser                        avgt          1.962           ms/op
ClientSimple.getUser                          avgt          1.992           ms/op
ClientSimple.listUser                         avgt          3.751           ms/op
ClientSimple.createUser                     sample  15209   2.110 ± 0.036   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.504           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.015           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.540           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.757           ms/op
ClientSimple.createUser:createUser·p0.99    sample          4.243           ms/op
ClientSimple.createUser:createUser·p0.999   sample         28.305           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         32.526           ms/op
ClientSimple.createUser:createUser·p1.00    sample         34.472           ms/op
ClientSimple.existUser                      sample  18742   1.708 ± 0.007   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.422           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.683           ms/op
ClientSimple.existUser:existUser·p0.90      sample          1.880           ms/op
ClientSimple.existUser:existUser·p0.95      sample          1.987           ms/op
ClientSimple.existUser:existUser·p0.99      sample          2.577           ms/op
ClientSimple.existUser:existUser·p0.999     sample          5.794           ms/op
ClientSimple.existUser:existUser·p0.9999    sample          6.738           ms/op
ClientSimple.existUser:existUser·p1.00      sample          8.249           ms/op
ClientSimple.getUser                        sample  13518   2.384 ± 0.026   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.783           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.269           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.994           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.187           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.260           ms/op
ClientSimple.getUser:getUser·p0.999         sample         17.413           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         17.976           ms/op
ClientSimple.getUser:getUser·p1.00          sample         18.022           ms/op
ClientSimple.listUser                       sample   8981   3.564 ± 0.035   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.417           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.531           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.317           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.932           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.098           ms/op
ClientSimple.listUser:listUser·p0.999       sample         14.762           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         15.712           ms/op
ClientSimple.listUser:listUser·p1.00        sample         15.712           ms/op

Benchmark result is saved to 1719425532135.json
