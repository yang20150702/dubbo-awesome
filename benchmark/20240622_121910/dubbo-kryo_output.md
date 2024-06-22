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
# Warmup Iteration   1: 1.979 ops/ms
Iteration   1: 7.291 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.291 ops/ms


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
# Warmup Iteration   1: 6.563 ops/ms
Iteration   1: 12.510 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.510 ops/ms


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
# Warmup Iteration   1: 7.275 ops/ms
Iteration   1: 15.448 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  15.448 ops/ms


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
# Warmup Iteration   1: 5.383 ops/ms
Iteration   1: 8.394 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.394 ops/ms


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
# Warmup Iteration   1: 3.839 ±(99.9%) 0.077 ms/op
Iteration   1: 2.044 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.044 ms/op


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
# Warmup Iteration   1: 2.806 ±(99.9%) 0.050 ms/op
Iteration   1: 1.835 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.835 ms/op


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
# Warmup Iteration   1: 3.261 ±(99.9%) 0.049 ms/op
Iteration   1: 1.938 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.938 ms/op


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
# Warmup Iteration   1: 4.626 ±(99.9%) 0.094 ms/op
Iteration   1: 3.519 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.519 ms/op


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
# Warmup Iteration   1: 3.374 ±(99.9%) 0.077 ms/op
Iteration   1: 2.375 ±(99.9%) 0.048 ms/op
                 createUser·p0.00:   0.961 ms/op
                 createUser·p0.50:   2.159 ms/op
                 createUser·p0.90:   2.990 ms/op
                 createUser·p0.95:   3.260 ms/op
                 createUser·p0.99:   7.074 ms/op
                 createUser·p0.999:  33.292 ms/op
                 createUser·p0.9999: 34.808 ms/op
                 createUser·p1.00:   35.193 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13452
  mean =      2.375 ±(99.9%) 0.048 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9292 
    [ 2.500,  5.000) = 3955 
    [ 5.000,  7.500) = 76 
    [ 7.500, 10.000) = 92 
    [10.000, 12.500) = 5 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 10 
    [32.500, 35.000) = 21 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.961 ms/op
     p(50.0000) =      2.159 ms/op
     p(90.0000) =      2.990 ms/op
     p(95.0000) =      3.260 ms/op
     p(99.0000) =      7.074 ms/op
     p(99.9000) =     33.292 ms/op
     p(99.9900) =     34.808 ms/op
     p(99.9990) =     35.193 ms/op
     p(99.9999) =     35.193 ms/op
    p(100.0000) =     35.193 ms/op


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
# Warmup Iteration   1: 3.121 ±(99.9%) 0.079 ms/op
Iteration   1: 1.927 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   0.674 ms/op
                 existUser·p0.50:   1.845 ms/op
                 existUser·p0.90:   2.327 ms/op
                 existUser·p0.95:   2.466 ms/op
                 existUser·p0.99:   3.956 ms/op
                 existUser·p0.999:  15.225 ms/op
                 existUser·p0.9999: 16.504 ms/op
                 existUser·p1.00:   16.712 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16677
  mean =      1.927 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 480 
    [ 1.250,  2.500) = 15463 
    [ 2.500,  3.750) = 562 
    [ 3.750,  5.000) = 69 
    [ 5.000,  6.250) = 39 
    [ 6.250,  7.500) = 28 
    [ 7.500,  8.750) = 4 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 11 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 15 
    [16.250, 17.500) = 4 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.674 ms/op
     p(50.0000) =      1.845 ms/op
     p(90.0000) =      2.327 ms/op
     p(95.0000) =      2.466 ms/op
     p(99.0000) =      3.956 ms/op
     p(99.9000) =     15.225 ms/op
     p(99.9900) =     16.504 ms/op
     p(99.9990) =     16.712 ms/op
     p(99.9999) =     16.712 ms/op
    p(100.0000) =     16.712 ms/op


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
# Warmup Iteration   1: 3.407 ±(99.9%) 0.087 ms/op
Iteration   1: 1.770 ±(99.9%) 0.025 ms/op
                 getUser·p0.00:   0.876 ms/op
                 getUser·p0.50:   1.642 ms/op
                 getUser·p0.90:   2.154 ms/op
                 getUser·p0.95:   2.376 ms/op
                 getUser·p0.99:   3.228 ms/op
                 getUser·p0.999:  21.823 ms/op
                 getUser·p0.9999: 22.206 ms/op
                 getUser·p1.00:   22.315 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 18332
  mean =      1.770 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17757 
    [ 2.500,  5.000) = 505 
    [ 5.000,  7.500) = 5 
    [ 7.500, 10.000) = 1 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.876 ms/op
     p(50.0000) =      1.642 ms/op
     p(90.0000) =      2.154 ms/op
     p(95.0000) =      2.376 ms/op
     p(99.0000) =      3.228 ms/op
     p(99.9000) =     21.823 ms/op
     p(99.9900) =     22.206 ms/op
     p(99.9990) =     22.315 ms/op
     p(99.9999) =     22.315 ms/op
    p(100.0000) =     22.315 ms/op


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
# Warmup Iteration   1: 4.037 ±(99.9%) 0.109 ms/op
Iteration   1: 3.176 ±(99.9%) 0.040 ms/op
                 listUser·p0.00:   0.813 ms/op
                 listUser·p0.50:   2.884 ms/op
                 listUser·p0.90:   3.973 ms/op
                 listUser·p0.95:   4.375 ms/op
                 listUser·p0.99:   6.002 ms/op
                 listUser·p0.999:  20.073 ms/op
                 listUser·p0.9999: 24.019 ms/op
                 listUser·p1.00:   24.019 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10106
  mean =      3.176 ±(99.9%) 0.040 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 458 
    [ 2.500,  5.000) = 9372 
    [ 5.000,  7.500) = 208 
    [ 7.500, 10.000) = 15 
    [10.000, 12.500) = 21 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.813 ms/op
     p(50.0000) =      2.884 ms/op
     p(90.0000) =      3.973 ms/op
     p(95.0000) =      4.375 ms/op
     p(99.0000) =      6.002 ms/op
     p(99.9000) =     20.073 ms/op
     p(99.9900) =     24.019 ms/op
     p(99.9990) =     24.019 ms/op
     p(99.9999) =     24.019 ms/op
    p(100.0000) =     24.019 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.291          ops/ms
ClientSimple.existUser                       thrpt         12.510          ops/ms
ClientSimple.getUser                         thrpt         15.448          ops/ms
ClientSimple.listUser                        thrpt          8.394          ops/ms
ClientSimple.createUser                       avgt          2.044           ms/op
ClientSimple.existUser                        avgt          1.835           ms/op
ClientSimple.getUser                          avgt          1.938           ms/op
ClientSimple.listUser                         avgt          3.519           ms/op
ClientSimple.createUser                     sample  13452   2.375 ± 0.048   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.961           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.159           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.990           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.260           ms/op
ClientSimple.createUser:createUser·p0.99    sample          7.074           ms/op
ClientSimple.createUser:createUser·p0.999   sample         33.292           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         34.808           ms/op
ClientSimple.createUser:createUser·p1.00    sample         35.193           ms/op
ClientSimple.existUser                      sample  16677   1.927 ± 0.019   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.674           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.845           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.327           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.466           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.956           ms/op
ClientSimple.existUser:existUser·p0.999     sample         15.225           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         16.504           ms/op
ClientSimple.existUser:existUser·p1.00      sample         16.712           ms/op
ClientSimple.getUser                        sample  18332   1.770 ± 0.025   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.876           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.642           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.154           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.376           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.228           ms/op
ClientSimple.getUser:getUser·p0.999         sample         21.823           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         22.206           ms/op
ClientSimple.getUser:getUser·p1.00          sample         22.315           ms/op
ClientSimple.listUser                       sample  10106   3.176 ± 0.040   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.813           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.884           ms/op
ClientSimple.listUser:listUser·p0.90        sample          3.973           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.375           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.002           ms/op
ClientSimple.listUser:listUser·p0.999       sample         20.073           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         24.019           ms/op
ClientSimple.listUser:listUser·p1.00        sample         24.019           ms/op

Benchmark result is saved to 1719058506557.json
