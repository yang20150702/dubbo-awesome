# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 1.776 ops/ms
Iteration   1: 6.744 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.744 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 5.113 ops/ms
Iteration   1: 12.227 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.227 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 16.67% complete, ETA 00:01:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.907 ops/ms
Iteration   1: 12.479 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.479 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 4.108 ops/ms
Iteration   1: 8.822 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.822 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.864 ±(99.9%) 0.071 ms/op
Iteration   1: 2.132 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.132 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.281 ±(99.9%) 0.060 ms/op
Iteration   1: 1.966 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.966 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 3.185 ±(99.9%) 0.049 ms/op
Iteration   1: 2.173 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.173 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 4.607 ±(99.9%) 0.097 ms/op
Iteration   1: 4.082 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  4.082 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.527 ±(99.9%) 0.084 ms/op
Iteration   1: 2.346 ±(99.9%) 0.038 ms/op
                 createUser·p0.00:   0.825 ms/op
                 createUser·p0.50:   2.171 ms/op
                 createUser·p0.90:   2.822 ms/op
                 createUser·p0.95:   3.035 ms/op
                 createUser·p0.99:   9.025 ms/op
                 createUser·p0.999:  20.666 ms/op
                 createUser·p0.9999: 22.643 ms/op
                 createUser·p1.00:   22.643 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13660
  mean =      2.346 ±(99.9%) 0.038 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9855 
    [ 2.500,  5.000) = 3579 
    [ 5.000,  7.500) = 34 
    [ 7.500, 10.000) = 106 
    [10.000, 12.500) = 22 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.825 ms/op
     p(50.0000) =      2.171 ms/op
     p(90.0000) =      2.822 ms/op
     p(95.0000) =      3.035 ms/op
     p(99.0000) =      9.025 ms/op
     p(99.9000) =     20.666 ms/op
     p(99.9900) =     22.643 ms/op
     p(99.9990) =     22.643 ms/op
     p(99.9999) =     22.643 ms/op
    p(100.0000) =     22.643 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 2.969 ±(99.9%) 0.067 ms/op
Iteration   1: 1.925 ±(99.9%) 0.023 ms/op
                 existUser·p0.00:   0.770 ms/op
                 existUser·p0.50:   1.802 ms/op
                 existUser·p0.90:   2.351 ms/op
                 existUser·p0.95:   2.535 ms/op
                 existUser·p0.99:   3.613 ms/op
                 existUser·p0.999:  16.522 ms/op
                 existUser·p0.9999: 16.625 ms/op
                 existUser·p1.00:   16.646 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16595
  mean =      1.925 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 210 
    [ 1.250,  2.500) = 15446 
    [ 2.500,  3.750) = 789 
    [ 3.750,  5.000) = 51 
    [ 5.000,  6.250) = 35 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 32 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.770 ms/op
     p(50.0000) =      1.802 ms/op
     p(90.0000) =      2.351 ms/op
     p(95.0000) =      2.535 ms/op
     p(99.0000) =      3.613 ms/op
     p(99.9000) =     16.522 ms/op
     p(99.9900) =     16.625 ms/op
     p(99.9990) =     16.646 ms/op
     p(99.9999) =     16.646 ms/op
    p(100.0000) =     16.646 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.471 ±(99.9%) 0.100 ms/op
Iteration   1: 2.261 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   0.779 ms/op
                 getUser·p0.50:   2.183 ms/op
                 getUser·p0.90:   2.822 ms/op
                 getUser·p0.95:   2.998 ms/op
                 getUser·p0.99:   3.950 ms/op
                 getUser·p0.999:  15.660 ms/op
                 getUser·p0.9999: 17.159 ms/op
                 getUser·p1.00:   17.269 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14167
  mean =      2.261 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 155 
    [ 1.250,  2.500) = 10318 
    [ 2.500,  3.750) = 3522 
    [ 3.750,  5.000) = 76 
    [ 5.000,  6.250) = 40 
    [ 6.250,  7.500) = 10 
    [ 7.500,  8.750) = 14 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 8 
    [15.000, 16.250) = 21 
    [16.250, 17.500) = 3 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.779 ms/op
     p(50.0000) =      2.183 ms/op
     p(90.0000) =      2.822 ms/op
     p(95.0000) =      2.998 ms/op
     p(99.0000) =      3.950 ms/op
     p(99.9000) =     15.660 ms/op
     p(99.9900) =     17.159 ms/op
     p(99.9990) =     17.269 ms/op
     p(99.9999) =     17.269 ms/op
    p(100.0000) =     17.269 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.617 ±(99.9%) 0.122 ms/op
Iteration   1: 3.598 ±(99.9%) 0.043 ms/op
                 listUser·p0.00:   0.743 ms/op
                 listUser·p0.50:   3.531 ms/op
                 listUser·p0.90:   4.399 ms/op
                 listUser·p0.95:   4.719 ms/op
                 listUser·p0.99:   6.824 ms/op
                 listUser·p0.999:  19.861 ms/op
                 listUser·p0.9999: 20.677 ms/op
                 listUser·p1.00:   20.677 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8897
  mean =      3.598 ±(99.9%) 0.043 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 426 
    [ 2.500,  5.000) = 8230 
    [ 5.000,  7.500) = 174 
    [ 7.500, 10.000) = 34 
    [10.000, 12.500) = 1 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 27 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.743 ms/op
     p(50.0000) =      3.531 ms/op
     p(90.0000) =      4.399 ms/op
     p(95.0000) =      4.719 ms/op
     p(99.0000) =      6.824 ms/op
     p(99.9000) =     19.861 ms/op
     p(99.9900) =     20.677 ms/op
     p(99.9990) =     20.677 ms/op
     p(99.9999) =     20.677 ms/op
    p(100.0000) =     20.677 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.744          ops/ms
ClientSimple.existUser                       thrpt         12.227          ops/ms
ClientSimple.getUser                         thrpt         12.479          ops/ms
ClientSimple.listUser                        thrpt          8.822          ops/ms
ClientSimple.createUser                       avgt          2.132           ms/op
ClientSimple.existUser                        avgt          1.966           ms/op
ClientSimple.getUser                          avgt          2.173           ms/op
ClientSimple.listUser                         avgt          4.082           ms/op
ClientSimple.createUser                     sample  13660   2.346 ± 0.038   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.825           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.171           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.822           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.035           ms/op
ClientSimple.createUser:createUser·p0.99    sample          9.025           ms/op
ClientSimple.createUser:createUser·p0.999   sample         20.666           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         22.643           ms/op
ClientSimple.createUser:createUser·p1.00    sample         22.643           ms/op
ClientSimple.existUser                      sample  16595   1.925 ± 0.023   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.770           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.802           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.351           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.535           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.613           ms/op
ClientSimple.existUser:existUser·p0.999     sample         16.522           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         16.625           ms/op
ClientSimple.existUser:existUser·p1.00      sample         16.646           ms/op
ClientSimple.getUser                        sample  14167   2.261 ± 0.023   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.779           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.183           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.822           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.998           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.950           ms/op
ClientSimple.getUser:getUser·p0.999         sample         15.660           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         17.159           ms/op
ClientSimple.getUser:getUser·p1.00          sample         17.269           ms/op
ClientSimple.listUser                       sample   8897   3.598 ± 0.043   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.743           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.531           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.399           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.719           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.824           ms/op
ClientSimple.listUser:listUser·p0.999       sample         19.861           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         20.677           ms/op
ClientSimple.listUser:listUser·p1.00        sample         20.677           ms/op

Benchmark result is saved to 1713463868224.json
