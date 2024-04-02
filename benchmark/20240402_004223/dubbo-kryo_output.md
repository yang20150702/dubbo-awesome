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
# Warmup Iteration   1: 2.243 ops/ms
Iteration   1: 7.344 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.344 ops/ms


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
# Warmup Iteration   1: 6.674 ops/ms
Iteration   1: 14.252 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  14.252 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.870 ops/ms
Iteration   1: 13.155 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.155 ops/ms


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
# Warmup Iteration   1: 6.038 ops/ms
Iteration   1: 8.810 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.810 ops/ms


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
# Warmup Iteration   1: 4.128 ±(99.9%) 0.064 ms/op
Iteration   1: 1.896 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  1.896 ms/op


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
# Warmup Iteration   1: 3.313 ±(99.9%) 0.051 ms/op
Iteration   1: 1.794 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.794 ms/op


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
# Warmup Iteration   1: 3.098 ±(99.9%) 0.047 ms/op
Iteration   1: 2.123 ±(99.9%) 0.051 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.123 ms/op


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
# Warmup Iteration   1: 4.487 ±(99.9%) 0.089 ms/op
Iteration   1: 3.294 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.294 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 3.453 ±(99.9%) 0.080 ms/op
Iteration   1: 2.252 ±(99.9%) 0.032 ms/op
                 createUser·p0.00:   0.433 ms/op
                 createUser·p0.50:   2.187 ms/op
                 createUser·p0.90:   2.761 ms/op
                 createUser·p0.95:   3.052 ms/op
                 createUser·p0.99:   5.880 ms/op
                 createUser·p0.999:  22.407 ms/op
                 createUser·p0.9999: 26.084 ms/op
                 createUser·p1.00:   26.608 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14202
  mean =      2.252 ±(99.9%) 0.032 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11245 
    [ 2.500,  5.000) = 2800 
    [ 5.000,  7.500) = 125 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 20 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.433 ms/op
     p(50.0000) =      2.187 ms/op
     p(90.0000) =      2.761 ms/op
     p(95.0000) =      3.052 ms/op
     p(99.0000) =      5.880 ms/op
     p(99.9000) =     22.407 ms/op
     p(99.9900) =     26.084 ms/op
     p(99.9990) =     26.608 ms/op
     p(99.9999) =     26.608 ms/op
    p(100.0000) =     26.608 ms/op


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
# Warmup Iteration   1: 3.039 ±(99.9%) 0.069 ms/op
Iteration   1: 2.244 ±(99.9%) 0.047 ms/op
                 existUser·p0.00:   0.575 ms/op
                 existUser·p0.50:   2.150 ms/op
                 existUser·p0.90:   2.646 ms/op
                 existUser·p0.95:   2.810 ms/op
                 existUser·p0.99:   3.309 ms/op
                 existUser·p0.999:  34.865 ms/op
                 existUser·p0.9999: 35.558 ms/op
                 existUser·p1.00:   35.586 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 14259
  mean =      2.244 ±(99.9%) 0.047 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11541 
    [ 2.500,  5.000) = 2653 
    [ 5.000,  7.500) = 1 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 23 
    [15.000, 17.500) = 8 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 24 
    [35.000, 37.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      0.575 ms/op
     p(50.0000) =      2.150 ms/op
     p(90.0000) =      2.646 ms/op
     p(95.0000) =      2.810 ms/op
     p(99.0000) =      3.309 ms/op
     p(99.9000) =     34.865 ms/op
     p(99.9900) =     35.558 ms/op
     p(99.9990) =     35.586 ms/op
     p(99.9999) =     35.586 ms/op
    p(100.0000) =     35.586 ms/op


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
# Warmup Iteration   1: 3.195 ±(99.9%) 0.073 ms/op
Iteration   1: 1.900 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   0.549 ms/op
                 getUser·p0.50:   1.776 ms/op
                 getUser·p0.90:   2.408 ms/op
                 getUser·p0.95:   2.646 ms/op
                 getUser·p0.99:   4.456 ms/op
                 getUser·p0.999:  13.185 ms/op
                 getUser·p0.9999: 13.423 ms/op
                 getUser·p1.00:   13.435 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 17261
  mean =      1.900 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 72 
    [ 1.250,  2.500) = 15835 
    [ 2.500,  3.750) = 1162 
    [ 3.750,  5.000) = 129 
    [ 5.000,  6.250) = 27 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 3 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.549 ms/op
     p(50.0000) =      1.776 ms/op
     p(90.0000) =      2.408 ms/op
     p(95.0000) =      2.646 ms/op
     p(99.0000) =      4.456 ms/op
     p(99.9000) =     13.185 ms/op
     p(99.9900) =     13.423 ms/op
     p(99.9990) =     13.435 ms/op
     p(99.9999) =     13.435 ms/op
    p(100.0000) =     13.435 ms/op


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
# Warmup Iteration   1: 4.487 ±(99.9%) 0.118 ms/op
Iteration   1: 3.769 ±(99.9%) 0.040 ms/op
                 listUser·p0.00:   1.206 ms/op
                 listUser·p0.50:   3.731 ms/op
                 listUser·p0.90:   4.489 ms/op
                 listUser·p0.95:   4.719 ms/op
                 listUser·p0.99:   6.054 ms/op
                 listUser·p0.999:  21.206 ms/op
                 listUser·p0.9999: 22.905 ms/op
                 listUser·p1.00:   22.905 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8428
  mean =      3.769 ±(99.9%) 0.040 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 346 
    [ 2.500,  5.000) = 7848 
    [ 5.000,  7.500) = 205 
    [ 7.500, 10.000) = 8 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.206 ms/op
     p(50.0000) =      3.731 ms/op
     p(90.0000) =      4.489 ms/op
     p(95.0000) =      4.719 ms/op
     p(99.0000) =      6.054 ms/op
     p(99.9000) =     21.206 ms/op
     p(99.9900) =     22.905 ms/op
     p(99.9990) =     22.905 ms/op
     p(99.9999) =     22.905 ms/op
    p(100.0000) =     22.905 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.344          ops/ms
ClientSimple.existUser                       thrpt         14.252          ops/ms
ClientSimple.getUser                         thrpt         13.155          ops/ms
ClientSimple.listUser                        thrpt          8.810          ops/ms
ClientSimple.createUser                       avgt          1.896           ms/op
ClientSimple.existUser                        avgt          1.794           ms/op
ClientSimple.getUser                          avgt          2.123           ms/op
ClientSimple.listUser                         avgt          3.294           ms/op
ClientSimple.createUser                     sample  14202   2.252 ± 0.032   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.433           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.187           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.761           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.052           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.880           ms/op
ClientSimple.createUser:createUser·p0.999   sample         22.407           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         26.084           ms/op
ClientSimple.createUser:createUser·p1.00    sample         26.608           ms/op
ClientSimple.existUser                      sample  14259   2.244 ± 0.047   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.575           ms/op
ClientSimple.existUser:existUser·p0.50      sample          2.150           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.646           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.810           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.309           ms/op
ClientSimple.existUser:existUser·p0.999     sample         34.865           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         35.558           ms/op
ClientSimple.existUser:existUser·p1.00      sample         35.586           ms/op
ClientSimple.getUser                        sample  17261   1.900 ± 0.017   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.549           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.776           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.408           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.646           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.456           ms/op
ClientSimple.getUser:getUser·p0.999         sample         13.185           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         13.423           ms/op
ClientSimple.getUser:getUser·p1.00          sample         13.435           ms/op
ClientSimple.listUser                       sample   8428   3.769 ± 0.040   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.206           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.731           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.489           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.719           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.054           ms/op
ClientSimple.listUser:listUser·p0.999       sample         21.206           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         22.905           ms/op
ClientSimple.listUser:listUser·p1.00        sample         22.905           ms/op

Benchmark result is saved to 1712018280175.json
