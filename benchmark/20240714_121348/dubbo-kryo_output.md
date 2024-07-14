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
# Warmup Iteration   1: 1.347 ops/ms
Iteration   1: 6.963 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.963 ops/ms


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
# Warmup Iteration   1: 6.282 ops/ms
Iteration   1: 12.817 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.817 ops/ms


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
# Warmup Iteration   1: 5.835 ops/ms
Iteration   1: 11.312 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.312 ops/ms


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
# Warmup Iteration   1: 4.529 ops/ms
Iteration   1: 8.493 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.493 ops/ms


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
# Warmup Iteration   1: 3.858 ±(99.9%) 0.072 ms/op
Iteration   1: 2.127 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.127 ms/op


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
# Warmup Iteration   1: 3.126 ±(99.9%) 0.048 ms/op
Iteration   1: 1.895 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.895 ms/op


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
# Warmup Iteration   1: 4.014 ±(99.9%) 0.073 ms/op
Iteration   1: 1.932 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.932 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 4.521 ±(99.9%) 0.084 ms/op
Iteration   1: 3.370 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.370 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 3.531 ±(99.9%) 0.099 ms/op
Iteration   1: 2.118 ±(99.9%) 0.033 ms/op
                 createUser·p0.00:   0.846 ms/op
                 createUser·p0.50:   1.909 ms/op
                 createUser·p0.90:   2.638 ms/op
                 createUser·p0.95:   2.884 ms/op
                 createUser·p0.99:   9.456 ms/op
                 createUser·p0.999:  18.739 ms/op
                 createUser·p0.9999: 18.809 ms/op
                 createUser·p1.00:   18.809 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15128
  mean =      2.118 ±(99.9%) 0.033 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 133 
    [ 1.250,  2.500) = 12866 
    [ 2.500,  3.750) = 1790 
    [ 3.750,  5.000) = 97 
    [ 5.000,  6.250) = 29 
    [ 6.250,  7.500) = 52 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 29 
    [10.000, 11.250) = 41 
    [11.250, 12.500) = 57 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 21 

  Percentiles, ms/op:
      p(0.0000) =      0.846 ms/op
     p(50.0000) =      1.909 ms/op
     p(90.0000) =      2.638 ms/op
     p(95.0000) =      2.884 ms/op
     p(99.0000) =      9.456 ms/op
     p(99.9000) =     18.739 ms/op
     p(99.9900) =     18.809 ms/op
     p(99.9990) =     18.809 ms/op
     p(99.9999) =     18.809 ms/op
    p(100.0000) =     18.809 ms/op


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
# Warmup Iteration   1: 3.185 ±(99.9%) 0.076 ms/op
Iteration   1: 1.881 ±(99.9%) 0.028 ms/op
                 existUser·p0.00:   0.545 ms/op
                 existUser·p0.50:   1.769 ms/op
                 existUser·p0.90:   2.273 ms/op
                 existUser·p0.95:   2.564 ms/op
                 existUser·p0.99:   4.351 ms/op
                 existUser·p0.999:  17.171 ms/op
                 existUser·p0.9999: 20.978 ms/op
                 existUser·p1.00:   21.070 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16990
  mean =      1.881 ±(99.9%) 0.028 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16029 
    [ 2.500,  5.000) = 846 
    [ 5.000,  7.500) = 27 
    [ 7.500, 10.000) = 5 
    [10.000, 12.500) = 4 
    [12.500, 15.000) = 37 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.545 ms/op
     p(50.0000) =      1.769 ms/op
     p(90.0000) =      2.273 ms/op
     p(95.0000) =      2.564 ms/op
     p(99.0000) =      4.351 ms/op
     p(99.9000) =     17.171 ms/op
     p(99.9900) =     20.978 ms/op
     p(99.9990) =     21.070 ms/op
     p(99.9999) =     21.070 ms/op
    p(100.0000) =     21.070 ms/op


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
# Warmup Iteration   1: 3.119 ±(99.9%) 0.072 ms/op
Iteration   1: 1.873 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   0.652 ms/op
                 getUser·p0.50:   1.763 ms/op
                 getUser·p0.90:   2.245 ms/op
                 getUser·p0.95:   2.585 ms/op
                 getUser·p0.99:   3.174 ms/op
                 getUser·p0.999:  12.665 ms/op
                 getUser·p0.9999: 13.013 ms/op
                 getUser·p1.00:   13.025 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 17341
  mean =      1.873 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 188 
    [ 1.250,  2.500) = 16103 
    [ 2.500,  3.750) = 942 
    [ 3.750,  5.000) = 20 
    [ 5.000,  6.250) = 19 
    [ 6.250,  7.500) = 4 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 32 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 31 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.652 ms/op
     p(50.0000) =      1.763 ms/op
     p(90.0000) =      2.245 ms/op
     p(95.0000) =      2.585 ms/op
     p(99.0000) =      3.174 ms/op
     p(99.9000) =     12.665 ms/op
     p(99.9900) =     13.013 ms/op
     p(99.9990) =     13.025 ms/op
     p(99.9999) =     13.025 ms/op
    p(100.0000) =     13.025 ms/op


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
# Warmup Iteration   1: 4.535 ±(99.9%) 0.141 ms/op
Iteration   1: 2.978 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   0.861 ms/op
                 listUser·p0.50:   2.765 ms/op
                 listUser·p0.90:   3.944 ms/op
                 listUser·p0.95:   4.252 ms/op
                 listUser·p0.99:   5.224 ms/op
                 listUser·p0.999:  8.770 ms/op
                 listUser·p0.9999: 10.056 ms/op
                 listUser·p1.00:   10.125 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10731
  mean =      2.978 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 0.000,  1.000) = 2 
    [ 1.000,  2.000) = 283 
    [ 2.000,  3.000) = 6928 
    [ 3.000,  4.000) = 2574 
    [ 4.000,  5.000) = 791 
    [ 5.000,  6.000) = 94 
    [ 6.000,  7.000) = 10 
    [ 7.000,  8.000) = 8 
    [ 8.000,  9.000) = 37 
    [ 9.000, 10.000) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.861 ms/op
     p(50.0000) =      2.765 ms/op
     p(90.0000) =      3.944 ms/op
     p(95.0000) =      4.252 ms/op
     p(99.0000) =      5.224 ms/op
     p(99.9000) =      8.770 ms/op
     p(99.9900) =     10.056 ms/op
     p(99.9990) =     10.125 ms/op
     p(99.9999) =     10.125 ms/op
    p(100.0000) =     10.125 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.963          ops/ms
ClientSimple.existUser                       thrpt         12.817          ops/ms
ClientSimple.getUser                         thrpt         11.312          ops/ms
ClientSimple.listUser                        thrpt          8.493          ops/ms
ClientSimple.createUser                       avgt          2.127           ms/op
ClientSimple.existUser                        avgt          1.895           ms/op
ClientSimple.getUser                          avgt          1.932           ms/op
ClientSimple.listUser                         avgt          3.370           ms/op
ClientSimple.createUser                     sample  15128   2.118 ± 0.033   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.846           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.909           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.638           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.884           ms/op
ClientSimple.createUser:createUser·p0.99    sample          9.456           ms/op
ClientSimple.createUser:createUser·p0.999   sample         18.739           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         18.809           ms/op
ClientSimple.createUser:createUser·p1.00    sample         18.809           ms/op
ClientSimple.existUser                      sample  16990   1.881 ± 0.028   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.545           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.769           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.273           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.564           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.351           ms/op
ClientSimple.existUser:existUser·p0.999     sample         17.171           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         20.978           ms/op
ClientSimple.existUser:existUser·p1.00      sample         21.070           ms/op
ClientSimple.getUser                        sample  17341   1.873 ± 0.017   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.652           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.763           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.245           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.585           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.174           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.665           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         13.013           ms/op
ClientSimple.getUser:getUser·p1.00          sample         13.025           ms/op
ClientSimple.listUser                       sample  10731   2.978 ± 0.024   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.861           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.765           ms/op
ClientSimple.listUser:listUser·p0.90        sample          3.944           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.252           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.224           ms/op
ClientSimple.listUser:listUser·p0.999       sample          8.770           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         10.056           ms/op
ClientSimple.listUser:listUser·p1.00        sample         10.125           ms/op

Benchmark result is saved to 1720958973973.json
