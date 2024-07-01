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
# Warmup Iteration   1: 1.816 ops/ms
Iteration   1: 7.847 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.847 ops/ms


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
# Warmup Iteration   1: 6.810 ops/ms
Iteration   1: 13.185 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.185 ops/ms


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
# Warmup Iteration   1: 5.316 ops/ms
Iteration   1: 13.056 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.056 ops/ms


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
# Warmup Iteration   1: 5.928 ops/ms
Iteration   1: 8.723 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.723 ops/ms


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
# Warmup Iteration   1: 4.019 ±(99.9%) 0.060 ms/op
Iteration   1: 2.155 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.155 ms/op


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
# Warmup Iteration   1: 2.851 ±(99.9%) 0.052 ms/op
Iteration   1: 2.005 ±(99.9%) 0.005 ms/op


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
# Warmup Iteration   1: 3.358 ±(99.9%) 0.060 ms/op
Iteration   1: 2.011 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.011 ms/op


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
# Warmup Iteration   1: 4.392 ±(99.9%) 0.103 ms/op
Iteration   1: 3.591 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.591 ms/op


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
# Warmup Iteration   1: 3.754 ±(99.9%) 0.106 ms/op
Iteration   1: 2.366 ±(99.9%) 0.023 ms/op
                 createUser·p0.00:   0.821 ms/op
                 createUser·p0.50:   2.281 ms/op
                 createUser·p0.90:   2.798 ms/op
                 createUser·p0.95:   2.987 ms/op
                 createUser·p0.99:   4.182 ms/op
                 createUser·p0.999:  15.483 ms/op
                 createUser·p0.9999: 15.981 ms/op
                 createUser·p1.00:   16.171 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13514
  mean =      2.366 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3 
    [ 1.250,  2.500) = 9462 
    [ 2.500,  3.750) = 3850 
    [ 3.750,  5.000) = 98 
    [ 5.000,  6.250) = 26 
    [ 6.250,  7.500) = 29 
    [ 7.500,  8.750) = 14 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 30 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.821 ms/op
     p(50.0000) =      2.281 ms/op
     p(90.0000) =      2.798 ms/op
     p(95.0000) =      2.987 ms/op
     p(99.0000) =      4.182 ms/op
     p(99.9000) =     15.483 ms/op
     p(99.9900) =     15.981 ms/op
     p(99.9990) =     16.171 ms/op
     p(99.9999) =     16.171 ms/op
    p(100.0000) =     16.171 ms/op


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
# Warmup Iteration   1: 2.983 ±(99.9%) 0.070 ms/op
Iteration   1: 2.075 ±(99.9%) 0.026 ms/op
                 existUser·p0.00:   0.478 ms/op
                 existUser·p0.50:   2.005 ms/op
                 existUser·p0.90:   2.481 ms/op
                 existUser·p0.95:   2.720 ms/op
                 existUser·p0.99:   4.850 ms/op
                 existUser·p0.999:  15.870 ms/op
                 existUser·p0.9999: 16.786 ms/op
                 existUser·p1.00:   17.007 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15391
  mean =      2.075 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 318 
    [ 1.250,  2.500) = 13636 
    [ 2.500,  3.750) = 1182 
    [ 3.750,  5.000) = 146 
    [ 5.000,  6.250) = 43 
    [ 6.250,  7.500) = 2 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 5 
    [13.750, 15.000) = 28 
    [15.000, 16.250) = 22 
    [16.250, 17.500) = 9 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.478 ms/op
     p(50.0000) =      2.005 ms/op
     p(90.0000) =      2.481 ms/op
     p(95.0000) =      2.720 ms/op
     p(99.0000) =      4.850 ms/op
     p(99.9000) =     15.870 ms/op
     p(99.9900) =     16.786 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.080 ±(99.9%) 0.071 ms/op
Iteration   1: 1.985 ±(99.9%) 0.033 ms/op
                 getUser·p0.00:   0.422 ms/op
                 getUser·p0.50:   1.847 ms/op
                 getUser·p0.90:   2.462 ms/op
                 getUser·p0.95:   2.699 ms/op
                 getUser·p0.99:   3.895 ms/op
                 getUser·p0.999:  21.037 ms/op
                 getUser·p0.9999: 21.685 ms/op
                 getUser·p1.00:   21.725 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16124
  mean =      1.985 ±(99.9%) 0.033 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14667 
    [ 2.500,  5.000) = 1334 
    [ 5.000,  7.500) = 57 
    [ 7.500, 10.000) = 2 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 59 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.422 ms/op
     p(50.0000) =      1.847 ms/op
     p(90.0000) =      2.462 ms/op
     p(95.0000) =      2.699 ms/op
     p(99.0000) =      3.895 ms/op
     p(99.9000) =     21.037 ms/op
     p(99.9900) =     21.685 ms/op
     p(99.9990) =     21.725 ms/op
     p(99.9999) =     21.725 ms/op
    p(100.0000) =     21.725 ms/op


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
# Warmup Iteration   1: 4.462 ±(99.9%) 0.143 ms/op
Iteration   1: 3.400 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   0.913 ms/op
                 listUser·p0.50:   3.346 ms/op
                 listUser·p0.90:   4.227 ms/op
                 listUser·p0.95:   4.562 ms/op
                 listUser·p0.99:   6.283 ms/op
                 listUser·p0.999:  8.001 ms/op
                 listUser·p0.9999: 11.747 ms/op
                 listUser·p1.00:   11.747 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9421
  mean =      3.400 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 17 
    [ 1.250,  2.500) = 703 
    [ 2.500,  3.750) = 5667 
    [ 3.750,  5.000) = 2769 
    [ 5.000,  6.250) = 160 
    [ 6.250,  7.500) = 84 
    [ 7.500,  8.750) = 20 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.913 ms/op
     p(50.0000) =      3.346 ms/op
     p(90.0000) =      4.227 ms/op
     p(95.0000) =      4.562 ms/op
     p(99.0000) =      6.283 ms/op
     p(99.9000) =      8.001 ms/op
     p(99.9900) =     11.747 ms/op
     p(99.9990) =     11.747 ms/op
     p(99.9999) =     11.747 ms/op
    p(100.0000) =     11.747 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.847          ops/ms
ClientSimple.existUser                       thrpt         13.185          ops/ms
ClientSimple.getUser                         thrpt         13.056          ops/ms
ClientSimple.listUser                        thrpt          8.723          ops/ms
ClientSimple.createUser                       avgt          2.155           ms/op
ClientSimple.existUser                        avgt          2.005           ms/op
ClientSimple.getUser                          avgt          2.011           ms/op
ClientSimple.listUser                         avgt          3.591           ms/op
ClientSimple.createUser                     sample  13514   2.366 ± 0.023   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.821           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.281           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.798           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.987           ms/op
ClientSimple.createUser:createUser·p0.99    sample          4.182           ms/op
ClientSimple.createUser:createUser·p0.999   sample         15.483           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         15.981           ms/op
ClientSimple.createUser:createUser·p1.00    sample         16.171           ms/op
ClientSimple.existUser                      sample  15391   2.075 ± 0.026   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.478           ms/op
ClientSimple.existUser:existUser·p0.50      sample          2.005           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.481           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.720           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.850           ms/op
ClientSimple.existUser:existUser·p0.999     sample         15.870           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         16.786           ms/op
ClientSimple.existUser:existUser·p1.00      sample         17.007           ms/op
ClientSimple.getUser                        sample  16124   1.985 ± 0.033   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.422           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.847           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.462           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.699           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.895           ms/op
ClientSimple.getUser:getUser·p0.999         sample         21.037           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         21.685           ms/op
ClientSimple.getUser:getUser·p1.00          sample         21.725           ms/op
ClientSimple.listUser                       sample   9421   3.400 ± 0.027   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.913           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.346           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.227           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.562           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.283           ms/op
ClientSimple.listUser:listUser·p0.999       sample          8.001           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         11.747           ms/op
ClientSimple.listUser:listUser·p1.00        sample         11.747           ms/op

Benchmark result is saved to 1719857551086.json
