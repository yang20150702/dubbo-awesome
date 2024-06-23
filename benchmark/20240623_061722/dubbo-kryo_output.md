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
# Warmup Iteration   1: 1.982 ops/ms
Iteration   1: 6.702 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.702 ops/ms


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
# Warmup Iteration   1: 5.633 ops/ms
Iteration   1: 12.392 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.392 ops/ms


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
# Warmup Iteration   1: 5.205 ops/ms
Iteration   1: 13.009 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.009 ops/ms


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
# Warmup Iteration   1: 5.563 ops/ms
Iteration   1: 8.609 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.609 ops/ms


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
# Warmup Iteration   1: 3.794 ±(99.9%) 0.076 ms/op
Iteration   1: 2.056 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.056 ms/op


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
# Warmup Iteration   1: 3.035 ±(99.9%) 0.040 ms/op
Iteration   1: 1.868 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.868 ms/op


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
# Warmup Iteration   1: 3.270 ±(99.9%) 0.047 ms/op
Iteration   1: 1.884 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.884 ms/op


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
# Warmup Iteration   1: 4.127 ±(99.9%) 0.087 ms/op
Iteration   1: 3.768 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.768 ms/op


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
# Warmup Iteration   1: 3.328 ±(99.9%) 0.075 ms/op
Iteration   1: 2.176 ±(99.9%) 0.029 ms/op
                 createUser·p0.00:   0.773 ms/op
                 createUser·p0.50:   2.025 ms/op
                 createUser·p0.90:   2.675 ms/op
                 createUser·p0.95:   2.814 ms/op
                 createUser·p0.99:   5.219 ms/op
                 createUser·p0.999:  15.598 ms/op
                 createUser·p0.9999: 16.664 ms/op
                 createUser·p1.00:   16.679 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14689
  mean =      2.176 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 85 
    [ 1.250,  2.500) = 12055 
    [ 2.500,  3.750) = 2292 
    [ 3.750,  5.000) = 79 
    [ 5.000,  6.250) = 63 
    [ 6.250,  7.500) = 5 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 19 
    [10.000, 11.250) = 9 
    [11.250, 12.500) = 20 
    [12.500, 13.750) = 5 
    [13.750, 15.000) = 31 
    [15.000, 16.250) = 22 
    [16.250, 17.500) = 2 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.773 ms/op
     p(50.0000) =      2.025 ms/op
     p(90.0000) =      2.675 ms/op
     p(95.0000) =      2.814 ms/op
     p(99.0000) =      5.219 ms/op
     p(99.9000) =     15.598 ms/op
     p(99.9900) =     16.664 ms/op
     p(99.9990) =     16.679 ms/op
     p(99.9999) =     16.679 ms/op
    p(100.0000) =     16.679 ms/op


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
# Warmup Iteration   1: 3.059 ±(99.9%) 0.070 ms/op
Iteration   1: 1.942 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   0.379 ms/op
                 existUser·p0.50:   1.896 ms/op
                 existUser·p0.90:   2.392 ms/op
                 existUser·p0.95:   2.544 ms/op
                 existUser·p0.99:   3.277 ms/op
                 existUser·p0.999:  13.582 ms/op
                 existUser·p0.9999: 14.249 ms/op
                 existUser·p1.00:   14.451 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16488
  mean =      1.942 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 433 
    [ 1.250,  2.500) = 14958 
    [ 2.500,  3.750) = 999 
    [ 3.750,  5.000) = 55 
    [ 5.000,  6.250) = 11 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 20 
    [13.750, 15.000) = 12 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.379 ms/op
     p(50.0000) =      1.896 ms/op
     p(90.0000) =      2.392 ms/op
     p(95.0000) =      2.544 ms/op
     p(99.0000) =      3.277 ms/op
     p(99.9000) =     13.582 ms/op
     p(99.9900) =     14.249 ms/op
     p(99.9990) =     14.451 ms/op
     p(99.9999) =     14.451 ms/op
    p(100.0000) =     14.451 ms/op


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
# Warmup Iteration   1: 3.264 ±(99.9%) 0.082 ms/op
Iteration   1: 1.991 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   0.800 ms/op
                 getUser·p0.50:   1.851 ms/op
                 getUser·p0.90:   2.429 ms/op
                 getUser·p0.95:   3.056 ms/op
                 getUser·p0.99:   4.276 ms/op
                 getUser·p0.999:  12.061 ms/op
                 getUser·p0.9999: 13.956 ms/op
                 getUser·p1.00:   14.303 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16056
  mean =      1.991 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 44 
    [ 1.250,  2.500) = 14646 
    [ 2.500,  3.750) = 1180 
    [ 3.750,  5.000) = 64 
    [ 5.000,  6.250) = 46 
    [ 6.250,  7.500) = 34 
    [ 7.500,  8.750) = 10 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 6 
    [11.250, 12.500) = 21 
    [12.500, 13.750) = 4 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.800 ms/op
     p(50.0000) =      1.851 ms/op
     p(90.0000) =      2.429 ms/op
     p(95.0000) =      3.056 ms/op
     p(99.0000) =      4.276 ms/op
     p(99.9000) =     12.061 ms/op
     p(99.9900) =     13.956 ms/op
     p(99.9990) =     14.303 ms/op
     p(99.9999) =     14.303 ms/op
    p(100.0000) =     14.303 ms/op


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
# Warmup Iteration   1: 4.414 ±(99.9%) 0.144 ms/op
Iteration   1: 3.618 ±(99.9%) 0.046 ms/op
                 listUser·p0.00:   1.305 ms/op
                 listUser·p0.50:   3.572 ms/op
                 listUser·p0.90:   4.407 ms/op
                 listUser·p0.95:   4.669 ms/op
                 listUser·p0.99:   6.021 ms/op
                 listUser·p0.999:  22.118 ms/op
                 listUser·p0.9999: 22.315 ms/op
                 listUser·p1.00:   22.315 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8828
  mean =      3.618 ±(99.9%) 0.046 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 556 
    [ 2.500,  5.000) = 8058 
    [ 5.000,  7.500) = 178 
    [ 7.500, 10.000) = 4 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.305 ms/op
     p(50.0000) =      3.572 ms/op
     p(90.0000) =      4.407 ms/op
     p(95.0000) =      4.669 ms/op
     p(99.0000) =      6.021 ms/op
     p(99.9000) =     22.118 ms/op
     p(99.9900) =     22.315 ms/op
     p(99.9990) =     22.315 ms/op
     p(99.9999) =     22.315 ms/op
    p(100.0000) =     22.315 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.702          ops/ms
ClientSimple.existUser                       thrpt         12.392          ops/ms
ClientSimple.getUser                         thrpt         13.009          ops/ms
ClientSimple.listUser                        thrpt          8.609          ops/ms
ClientSimple.createUser                       avgt          2.056           ms/op
ClientSimple.existUser                        avgt          1.868           ms/op
ClientSimple.getUser                          avgt          1.884           ms/op
ClientSimple.listUser                         avgt          3.768           ms/op
ClientSimple.createUser                     sample  14689   2.176 ± 0.029   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.773           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.025           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.675           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.814           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.219           ms/op
ClientSimple.createUser:createUser·p0.999   sample         15.598           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         16.664           ms/op
ClientSimple.createUser:createUser·p1.00    sample         16.679           ms/op
ClientSimple.existUser                      sample  16488   1.942 ± 0.017   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.379           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.896           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.392           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.544           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.277           ms/op
ClientSimple.existUser:existUser·p0.999     sample         13.582           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         14.249           ms/op
ClientSimple.existUser:existUser·p1.00      sample         14.451           ms/op
ClientSimple.getUser                        sample  16056   1.991 ± 0.018   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.800           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.851           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.429           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.056           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.276           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.061           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         13.956           ms/op
ClientSimple.getUser:getUser·p1.00          sample         14.303           ms/op
ClientSimple.listUser                       sample   8828   3.618 ± 0.046   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.305           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.572           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.407           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.669           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.021           ms/op
ClientSimple.listUser:listUser·p0.999       sample         22.118           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         22.315           ms/op
ClientSimple.listUser:listUser·p1.00        sample         22.315           ms/op

Benchmark result is saved to 1719123181229.json
