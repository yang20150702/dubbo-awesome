# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 2.630 ops/ms
Iteration   1: 6.702 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.702 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 8.33% complete, ETA 00:01:16
# Fork: 1 of 1
# Warmup Iteration   1: 5.505 ops/ms
Iteration   1: 13.037 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  13.037 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 16.67% complete, ETA 00:01:09
# Fork: 1 of 1
# Warmup Iteration   1: 4.200 ops/ms
Iteration   1: 9.180 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  9.180 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 25.00% complete, ETA 00:01:02
# Fork: 1 of 1
# Warmup Iteration   1: 2.436 ops/ms
Iteration   1: 3.748 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.748 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 33.33% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 5.894 ±(99.9%) 0.081 ms/op
Iteration   1: 3.154 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.154 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 41.67% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.461 ±(99.9%) 0.040 ms/op
Iteration   1: 2.005 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  2.005 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.623 ±(99.9%) 0.061 ms/op
Iteration   1: 2.972 ±(99.9%) 0.024 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  2.972 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 13.749 ±(99.9%) 0.299 ms/op
Iteration   1: 8.408 ±(99.9%) 0.099 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.408 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 4.988 ±(99.9%) 0.110 ms/op
Iteration   1: 3.223 ±(99.9%) 0.030 ms/op
                 createUser·p0.00:   1.247 ms/op
                 createUser·p0.50:   3.133 ms/op
                 createUser·p0.90:   3.928 ms/op
                 createUser·p0.95:   4.284 ms/op
                 createUser·p0.99:   5.181 ms/op
                 createUser·p0.999:  15.270 ms/op
                 createUser·p0.9999: 16.302 ms/op
                 createUser·p1.00:   16.302 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 9929
  mean =      3.223 ±(99.9%) 0.030 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2 
    [ 1.250,  2.500) = 1052 
    [ 2.500,  3.750) = 7466 
    [ 3.750,  5.000) = 1295 
    [ 5.000,  6.250) = 65 
    [ 6.250,  7.500) = 10 
    [ 7.500,  8.750) = 7 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 17 
    [15.000, 16.250) = 14 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.247 ms/op
     p(50.0000) =      3.133 ms/op
     p(90.0000) =      3.928 ms/op
     p(95.0000) =      4.284 ms/op
     p(99.0000) =      5.181 ms/op
     p(99.9000) =     15.270 ms/op
     p(99.9900) =     16.302 ms/op
     p(99.9990) =     16.302 ms/op
     p(99.9999) =     16.302 ms/op
    p(100.0000) =     16.302 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 75.00% complete, ETA 00:00:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.263 ±(99.9%) 0.077 ms/op
Iteration   1: 1.895 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   0.282 ms/op
                 existUser·p0.50:   1.720 ms/op
                 existUser·p0.90:   2.589 ms/op
                 existUser·p0.95:   2.744 ms/op
                 existUser·p0.99:   4.070 ms/op
                 existUser·p0.999:  5.735 ms/op
                 existUser·p0.9999: 5.816 ms/op
                 existUser·p1.00:   5.833 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 16865
  mean =      1.895 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 13 
    [0.500, 1.000) = 98 
    [1.000, 1.500) = 2334 
    [1.500, 2.000) = 9393 
    [2.000, 2.500) = 2776 
    [2.500, 3.000) = 1847 
    [3.000, 3.500) = 177 
    [3.500, 4.000) = 53 
    [4.000, 4.500) = 71 
    [4.500, 5.000) = 21 
    [5.000, 5.500) = 44 

  Percentiles, ms/op:
      p(0.0000) =      0.282 ms/op
     p(50.0000) =      1.720 ms/op
     p(90.0000) =      2.589 ms/op
     p(95.0000) =      2.744 ms/op
     p(99.0000) =      4.070 ms/op
     p(99.9000) =      5.735 ms/op
     p(99.9900) =      5.816 ms/op
     p(99.9990) =      5.833 ms/op
     p(99.9999) =      5.833 ms/op
    p(100.0000) =      5.833 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 83.33% complete, ETA 00:00:13
# Fork: 1 of 1
# Warmup Iteration   1: 4.465 ±(99.9%) 0.099 ms/op
Iteration   1: 2.980 ±(99.9%) 0.035 ms/op
                 getUser·p0.00:   0.714 ms/op
                 getUser·p0.50:   2.879 ms/op
                 getUser·p0.90:   3.723 ms/op
                 getUser·p0.95:   3.974 ms/op
                 getUser·p0.99:   5.815 ms/op
                 getUser·p0.999:  15.832 ms/op
                 getUser·p0.9999: 16.162 ms/op
                 getUser·p1.00:   16.171 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10715
  mean =      2.980 ±(99.9%) 0.035 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 14 
    [ 1.250,  2.500) = 3215 
    [ 2.500,  3.750) = 6487 
    [ 3.750,  5.000) = 864 
    [ 5.000,  6.250) = 45 
    [ 6.250,  7.500) = 26 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 11 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 21 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.714 ms/op
     p(50.0000) =      2.879 ms/op
     p(90.0000) =      3.723 ms/op
     p(95.0000) =      3.974 ms/op
     p(99.0000) =      5.815 ms/op
     p(99.9000) =     15.832 ms/op
     p(99.9900) =     16.162 ms/op
     p(99.9990) =     16.171 ms/op
     p(99.9999) =     16.171 ms/op
    p(100.0000) =     16.171 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 91.67% complete, ETA 00:00:06
# Fork: 1 of 1
# Warmup Iteration   1: 13.111 ±(99.9%) 0.451 ms/op
Iteration   1: 7.809 ±(99.9%) 0.116 ms/op
                 listUser·p0.00:   3.056 ms/op
                 listUser·p0.50:   7.356 ms/op
                 listUser·p0.90:   10.387 ms/op
                 listUser·p0.95:   11.272 ms/op
                 listUser·p0.99:   14.466 ms/op
                 listUser·p0.999:  26.174 ms/op
                 listUser·p0.9999: 45.023 ms/op
                 listUser·p1.00:   45.023 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 4133
  mean =      7.809 ±(99.9%) 0.116 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 112 
    [ 5.000, 10.000) = 3499 
    [10.000, 15.000) = 485 
    [15.000, 20.000) = 5 
    [20.000, 25.000) = 28 
    [25.000, 30.000) = 3 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 0 

  Percentiles, ms/op:
      p(0.0000) =      3.056 ms/op
     p(50.0000) =      7.356 ms/op
     p(90.0000) =     10.387 ms/op
     p(95.0000) =     11.272 ms/op
     p(99.0000) =     14.466 ms/op
     p(99.9000) =     26.174 ms/op
     p(99.9900) =     45.023 ms/op
     p(99.9990) =     45.023 ms/op
     p(99.9999) =     45.023 ms/op
    p(100.0000) =     45.023 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.702          ops/ms
Client.existUser                       thrpt         13.037          ops/ms
Client.getUser                         thrpt          9.180          ops/ms
Client.listUser                        thrpt          3.748          ops/ms
Client.createUser                       avgt          3.154           ms/op
Client.existUser                        avgt          2.005           ms/op
Client.getUser                          avgt          2.972           ms/op
Client.listUser                         avgt          8.408           ms/op
Client.createUser                     sample   9929   3.223 ± 0.030   ms/op
Client.createUser:createUser·p0.00    sample          1.247           ms/op
Client.createUser:createUser·p0.50    sample          3.133           ms/op
Client.createUser:createUser·p0.90    sample          3.928           ms/op
Client.createUser:createUser·p0.95    sample          4.284           ms/op
Client.createUser:createUser·p0.99    sample          5.181           ms/op
Client.createUser:createUser·p0.999   sample         15.270           ms/op
Client.createUser:createUser·p0.9999  sample         16.302           ms/op
Client.createUser:createUser·p1.00    sample         16.302           ms/op
Client.existUser                      sample  16865   1.895 ± 0.014   ms/op
Client.existUser:existUser·p0.00      sample          0.282           ms/op
Client.existUser:existUser·p0.50      sample          1.720           ms/op
Client.existUser:existUser·p0.90      sample          2.589           ms/op
Client.existUser:existUser·p0.95      sample          2.744           ms/op
Client.existUser:existUser·p0.99      sample          4.070           ms/op
Client.existUser:existUser·p0.999     sample          5.735           ms/op
Client.existUser:existUser·p0.9999    sample          5.816           ms/op
Client.existUser:existUser·p1.00      sample          5.833           ms/op
Client.getUser                        sample  10715   2.980 ± 0.035   ms/op
Client.getUser:getUser·p0.00          sample          0.714           ms/op
Client.getUser:getUser·p0.50          sample          2.879           ms/op
Client.getUser:getUser·p0.90          sample          3.723           ms/op
Client.getUser:getUser·p0.95          sample          3.974           ms/op
Client.getUser:getUser·p0.99          sample          5.815           ms/op
Client.getUser:getUser·p0.999         sample         15.832           ms/op
Client.getUser:getUser·p0.9999        sample         16.162           ms/op
Client.getUser:getUser·p1.00          sample         16.171           ms/op
Client.listUser                       sample   4133   7.809 ± 0.116   ms/op
Client.listUser:listUser·p0.00        sample          3.056           ms/op
Client.listUser:listUser·p0.50        sample          7.356           ms/op
Client.listUser:listUser·p0.90        sample         10.387           ms/op
Client.listUser:listUser·p0.95        sample         11.272           ms/op
Client.listUser:listUser·p0.99        sample         14.466           ms/op
Client.listUser:listUser·p0.999       sample         26.174           ms/op
Client.listUser:listUser·p0.9999      sample         45.023           ms/op
Client.listUser:listUser·p1.00        sample         45.023           ms/op
