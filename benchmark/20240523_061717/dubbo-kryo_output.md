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
# Warmup Iteration   1: 1.475 ops/ms
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
# Warmup Iteration   1: 5.727 ops/ms
Iteration   1: 13.123 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.123 ops/ms


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
# Warmup Iteration   1: 5.844 ops/ms
Iteration   1: 14.070 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  14.070 ops/ms


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
# Warmup Iteration   1: 4.873 ops/ms
Iteration   1: 7.854 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  7.854 ops/ms


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
# Warmup Iteration   1: 5.328 ±(99.9%) 0.223 ms/op
Iteration   1: 2.363 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.363 ms/op


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
# Warmup Iteration   1: 3.393 ±(99.9%) 0.060 ms/op
Iteration   1: 1.661 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.661 ms/op


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
# Warmup Iteration   1: 3.230 ±(99.9%) 0.058 ms/op
Iteration   1: 2.144 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.144 ms/op


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
# Warmup Iteration   1: 4.407 ±(99.9%) 0.077 ms/op
Iteration   1: 3.592 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.592 ms/op


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
# Warmup Iteration   1: 3.689 ±(99.9%) 0.117 ms/op
Iteration   1: 2.070 ±(99.9%) 0.036 ms/op
                 createUser·p0.00:   0.550 ms/op
                 createUser·p0.50:   1.925 ms/op
                 createUser·p0.90:   2.503 ms/op
                 createUser·p0.95:   2.744 ms/op
                 createUser·p0.99:   5.657 ms/op
                 createUser·p0.999:  28.639 ms/op
                 createUser·p0.9999: 31.669 ms/op
                 createUser·p1.00:   31.687 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15439
  mean =      2.070 ±(99.9%) 0.036 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13894 
    [ 2.500,  5.000) = 1352 
    [ 5.000,  7.500) = 161 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 3 
    [27.500, 30.000) = 19 
    [30.000, 32.500) = 10 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.550 ms/op
     p(50.0000) =      1.925 ms/op
     p(90.0000) =      2.503 ms/op
     p(95.0000) =      2.744 ms/op
     p(99.0000) =      5.657 ms/op
     p(99.9000) =     28.639 ms/op
     p(99.9900) =     31.669 ms/op
     p(99.9990) =     31.687 ms/op
     p(99.9999) =     31.687 ms/op
    p(100.0000) =     31.687 ms/op


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
# Warmup Iteration   1: 2.853 ±(99.9%) 0.071 ms/op
Iteration   1: 2.066 ±(99.9%) 0.028 ms/op
                 existUser·p0.00:   0.584 ms/op
                 existUser·p0.50:   1.884 ms/op
                 existUser·p0.90:   2.458 ms/op
                 existUser·p0.95:   2.777 ms/op
                 existUser·p0.99:   5.536 ms/op
                 existUser·p0.999:  15.352 ms/op
                 existUser·p0.9999: 15.821 ms/op
                 existUser·p1.00:   15.974 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15524
  mean =      2.066 ±(99.9%) 0.028 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 116 
    [ 1.250,  2.500) = 14014 
    [ 2.500,  3.750) = 1100 
    [ 3.750,  5.000) = 89 
    [ 5.000,  6.250) = 84 
    [ 6.250,  7.500) = 25 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 2 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 33 
    [12.500, 13.750) = 5 
    [13.750, 15.000) = 14 
    [15.000, 16.250) = 42 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.584 ms/op
     p(50.0000) =      1.884 ms/op
     p(90.0000) =      2.458 ms/op
     p(95.0000) =      2.777 ms/op
     p(99.0000) =      5.536 ms/op
     p(99.9000) =     15.352 ms/op
     p(99.9900) =     15.821 ms/op
     p(99.9990) =     15.974 ms/op
     p(99.9999) =     15.974 ms/op
    p(100.0000) =     15.974 ms/op


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
# Warmup Iteration   1: 3.333 ±(99.9%) 0.094 ms/op
Iteration   1: 1.769 ±(99.9%) 0.067 ms/op
                 getUser·p0.00:   0.626 ms/op
                 getUser·p0.50:   1.491 ms/op
                 getUser·p0.90:   2.187 ms/op
                 getUser·p0.95:   2.474 ms/op
                 getUser·p0.99:   4.268 ms/op
                 getUser·p0.999:  61.643 ms/op
                 getUser·p0.9999: 71.038 ms/op
                 getUser·p1.00:   72.221 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 18199
  mean =      1.769 ±(99.9%) 0.067 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 18069 
    [ 5.000, 10.000) = 20 
    [10.000, 15.000) = 57 
    [15.000, 20.000) = 13 
    [20.000, 25.000) = 3 
    [25.000, 30.000) = 1 
    [30.000, 35.000) = 3 
    [35.000, 40.000) = 2 
    [40.000, 45.000) = 3 
    [45.000, 50.000) = 2 
    [50.000, 55.000) = 3 
    [55.000, 60.000) = 3 
    [60.000, 65.000) = 3 
    [65.000, 70.000) = 5 
    [70.000, 75.000) = 12 

  Percentiles, ms/op:
      p(0.0000) =      0.626 ms/op
     p(50.0000) =      1.491 ms/op
     p(90.0000) =      2.187 ms/op
     p(95.0000) =      2.474 ms/op
     p(99.0000) =      4.268 ms/op
     p(99.9000) =     61.643 ms/op
     p(99.9900) =     71.038 ms/op
     p(99.9990) =     72.221 ms/op
     p(99.9999) =     72.221 ms/op
    p(100.0000) =     72.221 ms/op


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
# Warmup Iteration   1: 4.886 ±(99.9%) 0.155 ms/op
Iteration   1: 3.456 ±(99.9%) 0.045 ms/op
                 listUser·p0.00:   0.888 ms/op
                 listUser·p0.50:   3.301 ms/op
                 listUser·p0.90:   4.530 ms/op
                 listUser·p0.95:   4.997 ms/op
                 listUser·p0.99:   8.014 ms/op
                 listUser·p0.999:  16.727 ms/op
                 listUser·p0.9999: 17.596 ms/op
                 listUser·p1.00:   17.596 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9269
  mean =      3.456 ±(99.9%) 0.045 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 10 
    [ 1.250,  2.500) = 1289 
    [ 2.500,  3.750) = 4887 
    [ 3.750,  5.000) = 2621 
    [ 5.000,  6.250) = 217 
    [ 6.250,  7.500) = 132 
    [ 7.500,  8.750) = 48 
    [ 8.750, 10.000) = 8 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 24 
    [13.750, 15.000) = 5 
    [15.000, 16.250) = 15 
    [16.250, 17.500) = 11 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.888 ms/op
     p(50.0000) =      3.301 ms/op
     p(90.0000) =      4.530 ms/op
     p(95.0000) =      4.997 ms/op
     p(99.0000) =      8.014 ms/op
     p(99.9000) =     16.727 ms/op
     p(99.9900) =     17.596 ms/op
     p(99.9990) =     17.596 ms/op
     p(99.9999) =     17.596 ms/op
    p(100.0000) =     17.596 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.702          ops/ms
ClientSimple.existUser                       thrpt         13.123          ops/ms
ClientSimple.getUser                         thrpt         14.070          ops/ms
ClientSimple.listUser                        thrpt          7.854          ops/ms
ClientSimple.createUser                       avgt          2.363           ms/op
ClientSimple.existUser                        avgt          1.661           ms/op
ClientSimple.getUser                          avgt          2.144           ms/op
ClientSimple.listUser                         avgt          3.592           ms/op
ClientSimple.createUser                     sample  15439   2.070 ± 0.036   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.550           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.925           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.503           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.744           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.657           ms/op
ClientSimple.createUser:createUser·p0.999   sample         28.639           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         31.669           ms/op
ClientSimple.createUser:createUser·p1.00    sample         31.687           ms/op
ClientSimple.existUser                      sample  15524   2.066 ± 0.028   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.584           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.884           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.458           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.777           ms/op
ClientSimple.existUser:existUser·p0.99      sample          5.536           ms/op
ClientSimple.existUser:existUser·p0.999     sample         15.352           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         15.821           ms/op
ClientSimple.existUser:existUser·p1.00      sample         15.974           ms/op
ClientSimple.getUser                        sample  18199   1.769 ± 0.067   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.626           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.491           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.187           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.474           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.268           ms/op
ClientSimple.getUser:getUser·p0.999         sample         61.643           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         71.038           ms/op
ClientSimple.getUser:getUser·p1.00          sample         72.221           ms/op
ClientSimple.listUser                       sample   9269   3.456 ± 0.045   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.888           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.301           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.530           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.997           ms/op
ClientSimple.listUser:listUser·p0.99        sample          8.014           ms/op
ClientSimple.listUser:listUser·p0.999       sample         16.727           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         17.596           ms/op
ClientSimple.listUser:listUser·p1.00        sample         17.596           ms/op

Benchmark result is saved to 1716444795864.json
