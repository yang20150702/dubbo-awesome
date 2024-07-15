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
# Warmup Iteration   1: 1.062 ops/ms
Iteration   1: 5.561 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  5.561 ops/ms


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
# Warmup Iteration   1: 5.758 ops/ms
Iteration   1: 11.213 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.213 ops/ms


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
# Warmup Iteration   1: 4.869 ops/ms
Iteration   1: 12.410 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.410 ops/ms


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
# Warmup Iteration   1: 4.593 ops/ms
Iteration   1: 8.695 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.695 ops/ms


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
# Warmup Iteration   1: 3.525 ±(99.9%) 0.070 ms/op
Iteration   1: 2.339 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.339 ms/op


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
# Warmup Iteration   1: 3.480 ±(99.9%) 0.061 ms/op
Iteration   1: 2.105 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.105 ms/op


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
# Warmup Iteration   1: 3.545 ±(99.9%) 0.061 ms/op
Iteration   1: 1.973 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.973 ms/op


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
# Warmup Iteration   1: 5.352 ±(99.9%) 0.108 ms/op
Iteration   1: 3.883 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.883 ms/op


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
# Warmup Iteration   1: 3.101 ±(99.9%) 0.084 ms/op
Iteration   1: 2.267 ±(99.9%) 0.040 ms/op
                 createUser·p0.00:   0.547 ms/op
                 createUser·p0.50:   2.040 ms/op
                 createUser·p0.90:   2.761 ms/op
                 createUser·p0.95:   3.121 ms/op
                 createUser·p0.99:   9.336 ms/op
                 createUser·p0.999:  21.165 ms/op
                 createUser·p0.9999: 21.953 ms/op
                 createUser·p1.00:   22.020 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14103
  mean =      2.267 ±(99.9%) 0.040 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11577 
    [ 2.500,  5.000) = 2254 
    [ 5.000,  7.500) = 107 
    [ 7.500, 10.000) = 33 
    [10.000, 12.500) = 42 
    [12.500, 15.000) = 50 
    [15.000, 17.500) = 8 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.547 ms/op
     p(50.0000) =      2.040 ms/op
     p(90.0000) =      2.761 ms/op
     p(95.0000) =      3.121 ms/op
     p(99.0000) =      9.336 ms/op
     p(99.9000) =     21.165 ms/op
     p(99.9900) =     21.953 ms/op
     p(99.9990) =     22.020 ms/op
     p(99.9999) =     22.020 ms/op
    p(100.0000) =     22.020 ms/op


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
# Warmup Iteration   1: 2.861 ±(99.9%) 0.062 ms/op
Iteration   1: 2.180 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   0.501 ms/op
                 existUser·p0.50:   2.159 ms/op
                 existUser·p0.90:   2.568 ms/op
                 existUser·p0.95:   2.843 ms/op
                 existUser·p0.99:   4.922 ms/op
                 existUser·p0.999:  12.796 ms/op
                 existUser·p0.9999: 12.878 ms/op
                 existUser·p1.00:   12.878 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 14754
  mean =      2.180 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 286 
    [ 1.250,  2.500) = 12456 
    [ 2.500,  3.750) = 1791 
    [ 3.750,  5.000) = 78 
    [ 5.000,  6.250) = 106 
    [ 6.250,  7.500) = 4 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 12 
    [12.500, 13.750) = 20 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.501 ms/op
     p(50.0000) =      2.159 ms/op
     p(90.0000) =      2.568 ms/op
     p(95.0000) =      2.843 ms/op
     p(99.0000) =      4.922 ms/op
     p(99.9000) =     12.796 ms/op
     p(99.9900) =     12.878 ms/op
     p(99.9990) =     12.878 ms/op
     p(99.9999) =     12.878 ms/op
    p(100.0000) =     12.878 ms/op


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
# Warmup Iteration   1: 3.216 ±(99.9%) 0.072 ms/op
Iteration   1: 1.904 ±(99.9%) 0.026 ms/op
                 getUser·p0.00:   0.973 ms/op
                 getUser·p0.50:   1.761 ms/op
                 getUser·p0.90:   2.167 ms/op
                 getUser·p0.95:   2.408 ms/op
                 getUser·p0.99:   4.063 ms/op
                 getUser·p0.999:  20.978 ms/op
                 getUser·p0.9999: 21.189 ms/op
                 getUser·p1.00:   21.234 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16799
  mean =      1.904 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16186 
    [ 2.500,  5.000) = 481 
    [ 5.000,  7.500) = 68 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 30 
    [12.500, 15.000) = 2 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.973 ms/op
     p(50.0000) =      1.761 ms/op
     p(90.0000) =      2.167 ms/op
     p(95.0000) =      2.408 ms/op
     p(99.0000) =      4.063 ms/op
     p(99.9000) =     20.978 ms/op
     p(99.9900) =     21.189 ms/op
     p(99.9990) =     21.234 ms/op
     p(99.9999) =     21.234 ms/op
    p(100.0000) =     21.234 ms/op


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
# Warmup Iteration   1: 4.347 ±(99.9%) 0.143 ms/op
Iteration   1: 3.445 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   0.589 ms/op
                 listUser·p0.50:   3.383 ms/op
                 listUser·p0.90:   4.343 ms/op
                 listUser·p0.95:   4.637 ms/op
                 listUser·p0.99:   5.489 ms/op
                 listUser·p0.999:  6.708 ms/op
                 listUser·p0.9999: 6.963 ms/op
                 listUser·p1.00:   6.963 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9297
  mean =      3.445 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 3 
    [1.000, 1.500) = 2 
    [1.500, 2.000) = 59 
    [2.000, 2.500) = 633 
    [2.500, 3.000) = 1766 
    [3.000, 3.500) = 2928 
    [3.500, 4.000) = 2055 
    [4.000, 4.500) = 1205 
    [4.500, 5.000) = 406 
    [5.000, 5.500) = 150 
    [5.500, 6.000) = 47 
    [6.000, 6.500) = 22 

  Percentiles, ms/op:
      p(0.0000) =      0.589 ms/op
     p(50.0000) =      3.383 ms/op
     p(90.0000) =      4.343 ms/op
     p(95.0000) =      4.637 ms/op
     p(99.0000) =      5.489 ms/op
     p(99.9000) =      6.708 ms/op
     p(99.9900) =      6.963 ms/op
     p(99.9990) =      6.963 ms/op
     p(99.9999) =      6.963 ms/op
    p(100.0000) =      6.963 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          5.561          ops/ms
ClientSimple.existUser                       thrpt         11.213          ops/ms
ClientSimple.getUser                         thrpt         12.410          ops/ms
ClientSimple.listUser                        thrpt          8.695          ops/ms
ClientSimple.createUser                       avgt          2.339           ms/op
ClientSimple.existUser                        avgt          2.105           ms/op
ClientSimple.getUser                          avgt          1.973           ms/op
ClientSimple.listUser                         avgt          3.883           ms/op
ClientSimple.createUser                     sample  14103   2.267 ± 0.040   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.547           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.040           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.761           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.121           ms/op
ClientSimple.createUser:createUser·p0.99    sample          9.336           ms/op
ClientSimple.createUser:createUser·p0.999   sample         21.165           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         21.953           ms/op
ClientSimple.createUser:createUser·p1.00    sample         22.020           ms/op
ClientSimple.existUser                      sample  14754   2.180 ± 0.019   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.501           ms/op
ClientSimple.existUser:existUser·p0.50      sample          2.159           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.568           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.843           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.922           ms/op
ClientSimple.existUser:existUser·p0.999     sample         12.796           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         12.878           ms/op
ClientSimple.existUser:existUser·p1.00      sample         12.878           ms/op
ClientSimple.getUser                        sample  16799   1.904 ± 0.026   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.973           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.761           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.167           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.408           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.063           ms/op
ClientSimple.getUser:getUser·p0.999         sample         20.978           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         21.189           ms/op
ClientSimple.getUser:getUser·p1.00          sample         21.234           ms/op
ClientSimple.listUser                       sample   9297   3.445 ± 0.024   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.589           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.383           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.343           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.637           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.489           ms/op
ClientSimple.listUser:listUser·p0.999       sample          6.708           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          6.963           ms/op
ClientSimple.listUser:listUser·p1.00        sample          6.963           ms/op

Benchmark result is saved to 1721024077104.json
