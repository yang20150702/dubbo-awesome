# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 1.930 ops/ms
Iteration   1: 7.414 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.414 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 6.378 ops/ms
Iteration   1: 13.869 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.869 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 5.427 ops/ms
Iteration   1: 11.468 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.468 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 5.393 ops/ms
Iteration   1: 9.862 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.862 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.948 ±(99.9%) 0.068 ms/op
Iteration   1: 2.306 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.306 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.323 ±(99.9%) 0.057 ms/op
Iteration   1: 2.012 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.012 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 3.231 ±(99.9%) 0.062 ms/op
Iteration   1: 1.876 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.876 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 4.333 ±(99.9%) 0.071 ms/op
Iteration   1: 3.080 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.080 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.605 ±(99.9%) 0.081 ms/op
Iteration   1: 2.147 ±(99.9%) 0.032 ms/op
                 createUser·p0.00:   0.721 ms/op
                 createUser·p0.50:   1.972 ms/op
                 createUser·p0.90:   2.519 ms/op
                 createUser·p0.95:   2.744 ms/op
                 createUser·p0.99:   8.487 ms/op
                 createUser·p0.999:  15.057 ms/op
                 createUser·p0.9999: 15.401 ms/op
                 createUser·p1.00:   15.401 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14908
  mean =      2.147 ±(99.9%) 0.032 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 97 
    [ 1.250,  2.500) = 13225 
    [ 2.500,  3.750) = 1310 
    [ 3.750,  5.000) = 36 
    [ 5.000,  6.250) = 42 
    [ 6.250,  7.500) = 27 
    [ 7.500,  8.750) = 49 
    [ 8.750, 10.000) = 23 
    [10.000, 11.250) = 3 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 11 
    [13.750, 15.000) = 62 
    [15.000, 16.250) = 23 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.721 ms/op
     p(50.0000) =      1.972 ms/op
     p(90.0000) =      2.519 ms/op
     p(95.0000) =      2.744 ms/op
     p(99.0000) =      8.487 ms/op
     p(99.9000) =     15.057 ms/op
     p(99.9900) =     15.401 ms/op
     p(99.9990) =     15.401 ms/op
     p(99.9999) =     15.401 ms/op
    p(100.0000) =     15.401 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 2.953 ±(99.9%) 0.072 ms/op
Iteration   1: 1.845 ±(99.9%) 0.038 ms/op
                 existUser·p0.00:   0.638 ms/op
                 existUser·p0.50:   1.599 ms/op
                 existUser·p0.90:   2.351 ms/op
                 existUser·p0.95:   2.601 ms/op
                 existUser·p0.99:   4.833 ms/op
                 existUser·p0.999:  29.032 ms/op
                 existUser·p0.9999: 30.000 ms/op
                 existUser·p1.00:   30.048 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17301
  mean =      1.845 ±(99.9%) 0.038 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16157 
    [ 2.500,  5.000) = 973 
    [ 5.000,  7.500) = 43 
    [ 7.500, 10.000) = 57 
    [10.000, 12.500) = 7 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 5 
    [17.500, 20.000) = 27 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 31 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.638 ms/op
     p(50.0000) =      1.599 ms/op
     p(90.0000) =      2.351 ms/op
     p(95.0000) =      2.601 ms/op
     p(99.0000) =      4.833 ms/op
     p(99.9000) =     29.032 ms/op
     p(99.9900) =     30.000 ms/op
     p(99.9990) =     30.048 ms/op
     p(99.9999) =     30.048 ms/op
    p(100.0000) =     30.048 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.570 ±(99.9%) 0.109 ms/op
Iteration   1: 2.143 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   0.627 ms/op
                 getUser·p0.50:   1.944 ms/op
                 getUser·p0.90:   2.744 ms/op
                 getUser·p0.95:   3.002 ms/op
                 getUser·p0.99:   4.061 ms/op
                 getUser·p0.999:  16.531 ms/op
                 getUser·p0.9999: 17.565 ms/op
                 getUser·p1.00:   17.629 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14917
  mean =      2.143 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 68 
    [ 1.250,  2.500) = 12411 
    [ 2.500,  3.750) = 2246 
    [ 3.750,  5.000) = 75 
    [ 5.000,  6.250) = 33 
    [ 6.250,  7.500) = 20 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 30 
    [10.000, 11.250) = 2 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 17 
    [16.250, 17.500) = 14 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.627 ms/op
     p(50.0000) =      1.944 ms/op
     p(90.0000) =      2.744 ms/op
     p(95.0000) =      3.002 ms/op
     p(99.0000) =      4.061 ms/op
     p(99.9000) =     16.531 ms/op
     p(99.9900) =     17.565 ms/op
     p(99.9990) =     17.629 ms/op
     p(99.9999) =     17.629 ms/op
    p(100.0000) =     17.629 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.489 ±(99.9%) 0.140 ms/op
Iteration   1: 3.047 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   0.717 ms/op
                 listUser·p0.50:   2.855 ms/op
                 listUser·p0.90:   4.039 ms/op
                 listUser·p0.95:   4.268 ms/op
                 listUser·p0.99:   5.405 ms/op
                 listUser·p0.999:  7.176 ms/op
                 listUser·p0.9999: 9.483 ms/op
                 listUser·p1.00:   9.568 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10523
  mean =      3.047 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 0.000,  1.000) = 1 
    [ 1.000,  2.000) = 234 
    [ 2.000,  3.000) = 5776 
    [ 3.000,  4.000) = 3325 
    [ 4.000,  5.000) = 1039 
    [ 5.000,  6.000) = 84 
    [ 6.000,  7.000) = 36 
    [ 7.000,  8.000) = 27 
    [ 8.000,  9.000) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.717 ms/op
     p(50.0000) =      2.855 ms/op
     p(90.0000) =      4.039 ms/op
     p(95.0000) =      4.268 ms/op
     p(99.0000) =      5.405 ms/op
     p(99.9000) =      7.176 ms/op
     p(99.9900) =      9.483 ms/op
     p(99.9990) =      9.568 ms/op
     p(99.9999) =      9.568 ms/op
    p(100.0000) =      9.568 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.414          ops/ms
ClientSimple.existUser                       thrpt         13.869          ops/ms
ClientSimple.getUser                         thrpt         11.468          ops/ms
ClientSimple.listUser                        thrpt          9.862          ops/ms
ClientSimple.createUser                       avgt          2.306           ms/op
ClientSimple.existUser                        avgt          2.012           ms/op
ClientSimple.getUser                          avgt          1.876           ms/op
ClientSimple.listUser                         avgt          3.080           ms/op
ClientSimple.createUser                     sample  14908   2.147 ± 0.032   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.721           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.972           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.519           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.744           ms/op
ClientSimple.createUser:createUser·p0.99    sample          8.487           ms/op
ClientSimple.createUser:createUser·p0.999   sample         15.057           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         15.401           ms/op
ClientSimple.createUser:createUser·p1.00    sample         15.401           ms/op
ClientSimple.existUser                      sample  17301   1.845 ± 0.038   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.638           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.599           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.351           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.601           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.833           ms/op
ClientSimple.existUser:existUser·p0.999     sample         29.032           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         30.000           ms/op
ClientSimple.existUser:existUser·p1.00      sample         30.048           ms/op
ClientSimple.getUser                        sample  14917   2.143 ± 0.024   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.627           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.944           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.744           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.002           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.061           ms/op
ClientSimple.getUser:getUser·p0.999         sample         16.531           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         17.565           ms/op
ClientSimple.getUser:getUser·p1.00          sample         17.629           ms/op
ClientSimple.listUser                       sample  10523   3.047 ± 0.024   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.717           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.855           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.039           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.268           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.405           ms/op
ClientSimple.listUser:listUser·p0.999       sample          7.176           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          9.483           ms/op
ClientSimple.listUser:listUser·p1.00        sample          9.568           ms/op

Benchmark result is saved to 1722320020580.json
