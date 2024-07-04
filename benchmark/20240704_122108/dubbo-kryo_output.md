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
# Warmup Iteration   1: 1.508 ops/ms
Iteration   1: 6.016 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.016 ops/ms


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
# Warmup Iteration   1: 5.850 ops/ms
Iteration   1: 12.136 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.136 ops/ms


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
# Warmup Iteration   1: 6.160 ops/ms
Iteration   1: 13.722 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.722 ops/ms


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
# Warmup Iteration   1: 5.907 ops/ms
Iteration   1: 8.603 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.603 ops/ms


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
# Warmup Iteration   1: 3.739 ±(99.9%) 0.084 ms/op
Iteration   1: 2.229 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.229 ms/op


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
# Warmup Iteration   1: 3.018 ±(99.9%) 0.045 ms/op
Iteration   1: 1.885 ±(99.9%) 0.005 ms/op


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
# Warmup Iteration   1: 3.132 ±(99.9%) 0.058 ms/op
Iteration   1: 1.990 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.990 ms/op


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
# Warmup Iteration   1: 4.362 ±(99.9%) 0.073 ms/op
Iteration   1: 3.360 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.360 ms/op


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
# Warmup Iteration   1: 3.677 ±(99.9%) 0.091 ms/op
Iteration   1: 2.108 ±(99.9%) 0.045 ms/op
                 createUser·p0.00:   0.572 ms/op
                 createUser·p0.50:   1.833 ms/op
                 createUser·p0.90:   2.568 ms/op
                 createUser·p0.95:   2.724 ms/op
                 createUser·p0.99:   8.028 ms/op
                 createUser·p0.999:  29.786 ms/op
                 createUser·p0.9999: 30.261 ms/op
                 createUser·p1.00:   30.278 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15147
  mean =      2.108 ±(99.9%) 0.045 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13164 
    [ 2.500,  5.000) = 1756 
    [ 5.000,  7.500) = 52 
    [ 7.500, 10.000) = 47 
    [10.000, 12.500) = 27 
    [12.500, 15.000) = 54 
    [15.000, 17.500) = 15 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 26 
    [30.000, 32.500) = 6 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.572 ms/op
     p(50.0000) =      1.833 ms/op
     p(90.0000) =      2.568 ms/op
     p(95.0000) =      2.724 ms/op
     p(99.0000) =      8.028 ms/op
     p(99.9000) =     29.786 ms/op
     p(99.9900) =     30.261 ms/op
     p(99.9990) =     30.278 ms/op
     p(99.9999) =     30.278 ms/op
    p(100.0000) =     30.278 ms/op


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
# Warmup Iteration   1: 3.177 ±(99.9%) 0.064 ms/op
Iteration   1: 1.741 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   0.654 ms/op
                 existUser·p0.50:   1.628 ms/op
                 existUser·p0.90:   2.179 ms/op
                 existUser·p0.95:   2.396 ms/op
                 existUser·p0.99:   2.949 ms/op
                 existUser·p0.999:  13.926 ms/op
                 existUser·p0.9999: 14.280 ms/op
                 existUser·p1.00:   15.073 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 18349
  mean =      1.741 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 348 
    [ 1.250,  2.500) = 17315 
    [ 2.500,  3.750) = 632 
    [ 3.750,  5.000) = 22 
    [ 5.000,  6.250) = 0 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 8 
    [13.750, 15.000) = 23 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.654 ms/op
     p(50.0000) =      1.628 ms/op
     p(90.0000) =      2.179 ms/op
     p(95.0000) =      2.396 ms/op
     p(99.0000) =      2.949 ms/op
     p(99.9000) =     13.926 ms/op
     p(99.9900) =     14.280 ms/op
     p(99.9990) =     15.073 ms/op
     p(99.9999) =     15.073 ms/op
    p(100.0000) =     15.073 ms/op


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
# Warmup Iteration   1: 3.122 ±(99.9%) 0.075 ms/op
Iteration   1: 1.883 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   0.723 ms/op
                 getUser·p0.50:   1.797 ms/op
                 getUser·p0.90:   2.228 ms/op
                 getUser·p0.95:   2.425 ms/op
                 getUser·p0.99:   2.995 ms/op
                 getUser·p0.999:  14.516 ms/op
                 getUser·p0.9999: 14.685 ms/op
                 getUser·p1.00:   14.696 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16980
  mean =      1.883 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 123 
    [ 1.250,  2.500) = 16186 
    [ 2.500,  3.750) = 573 
    [ 3.750,  5.000) = 18 
    [ 5.000,  6.250) = 16 
    [ 6.250,  7.500) = 31 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.723 ms/op
     p(50.0000) =      1.797 ms/op
     p(90.0000) =      2.228 ms/op
     p(95.0000) =      2.425 ms/op
     p(99.0000) =      2.995 ms/op
     p(99.9000) =     14.516 ms/op
     p(99.9900) =     14.685 ms/op
     p(99.9990) =     14.696 ms/op
     p(99.9999) =     14.696 ms/op
    p(100.0000) =     14.696 ms/op


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
# Warmup Iteration   1: 4.509 ±(99.9%) 0.137 ms/op
Iteration   1: 2.958 ±(99.9%) 0.040 ms/op
                 listUser·p0.00:   1.057 ms/op
                 listUser·p0.50:   2.642 ms/op
                 listUser·p0.90:   3.973 ms/op
                 listUser·p0.95:   4.276 ms/op
                 listUser·p0.99:   5.784 ms/op
                 listUser·p0.999:  22.118 ms/op
                 listUser·p0.9999: 23.038 ms/op
                 listUser·p1.00:   23.101 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10804
  mean =      2.958 ±(99.9%) 0.040 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3294 
    [ 2.500,  5.000) = 7274 
    [ 5.000,  7.500) = 204 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.057 ms/op
     p(50.0000) =      2.642 ms/op
     p(90.0000) =      3.973 ms/op
     p(95.0000) =      4.276 ms/op
     p(99.0000) =      5.784 ms/op
     p(99.9000) =     22.118 ms/op
     p(99.9900) =     23.038 ms/op
     p(99.9990) =     23.101 ms/op
     p(99.9999) =     23.101 ms/op
    p(100.0000) =     23.101 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.016          ops/ms
ClientSimple.existUser                       thrpt         12.136          ops/ms
ClientSimple.getUser                         thrpt         13.722          ops/ms
ClientSimple.listUser                        thrpt          8.603          ops/ms
ClientSimple.createUser                       avgt          2.229           ms/op
ClientSimple.existUser                        avgt          1.885           ms/op
ClientSimple.getUser                          avgt          1.990           ms/op
ClientSimple.listUser                         avgt          3.360           ms/op
ClientSimple.createUser                     sample  15147   2.108 ± 0.045   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.572           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.833           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.568           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.724           ms/op
ClientSimple.createUser:createUser·p0.99    sample          8.028           ms/op
ClientSimple.createUser:createUser·p0.999   sample         29.786           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         30.261           ms/op
ClientSimple.createUser:createUser·p1.00    sample         30.278           ms/op
ClientSimple.existUser                      sample  18349   1.741 ± 0.015   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.654           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.628           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.179           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.396           ms/op
ClientSimple.existUser:existUser·p0.99      sample          2.949           ms/op
ClientSimple.existUser:existUser·p0.999     sample         13.926           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         14.280           ms/op
ClientSimple.existUser:existUser·p1.00      sample         15.073           ms/op
ClientSimple.getUser                        sample  16980   1.883 ± 0.017   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.723           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.797           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.228           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.425           ms/op
ClientSimple.getUser:getUser·p0.99          sample          2.995           ms/op
ClientSimple.getUser:getUser·p0.999         sample         14.516           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         14.685           ms/op
ClientSimple.getUser:getUser·p1.00          sample         14.696           ms/op
ClientSimple.listUser                       sample  10804   2.958 ± 0.040   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.057           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.642           ms/op
ClientSimple.listUser:listUser·p0.90        sample          3.973           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.276           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.784           ms/op
ClientSimple.listUser:listUser·p0.999       sample         22.118           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         23.038           ms/op
ClientSimple.listUser:listUser·p1.00        sample         23.101           ms/op

Benchmark result is saved to 1720095406625.json
