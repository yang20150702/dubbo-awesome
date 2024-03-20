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
# Warmup Iteration   1: 1.889 ops/ms
Iteration   1: 7.110 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.110 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 7.005 ops/ms
Iteration   1: 16.867 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  16.867 ops/ms


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
# Warmup Iteration   1: 6.498 ops/ms
Iteration   1: 13.163 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.163 ops/ms


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
# Warmup Iteration   1: 5.295 ops/ms
Iteration   1: 8.763 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.763 ops/ms


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
# Warmup Iteration   1: 3.707 ±(99.9%) 0.064 ms/op
Iteration   1: 2.004 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.004 ms/op


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
# Warmup Iteration   1: 2.884 ±(99.9%) 0.040 ms/op
Iteration   1: 1.772 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.772 ms/op


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
# Warmup Iteration   1: 3.244 ±(99.9%) 0.057 ms/op
Iteration   1: 2.056 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.056 ms/op


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
# Warmup Iteration   1: 4.743 ±(99.9%) 0.088 ms/op
Iteration   1: 3.070 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.070 ms/op


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
# Warmup Iteration   1: 3.420 ±(99.9%) 0.078 ms/op
Iteration   1: 2.092 ±(99.9%) 0.036 ms/op
                 createUser·p0.00:   0.460 ms/op
                 createUser·p0.50:   1.870 ms/op
                 createUser·p0.90:   2.454 ms/op
                 createUser·p0.95:   2.744 ms/op
                 createUser·p0.99:   8.384 ms/op
                 createUser·p0.999:  20.808 ms/op
                 createUser·p0.9999: 21.254 ms/op
                 createUser·p1.00:   21.529 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15227
  mean =      2.092 ±(99.9%) 0.036 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13837 
    [ 2.500,  5.000) = 1176 
    [ 5.000,  7.500) = 25 
    [ 7.500, 10.000) = 59 
    [10.000, 12.500) = 60 
    [12.500, 15.000) = 38 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.460 ms/op
     p(50.0000) =      1.870 ms/op
     p(90.0000) =      2.454 ms/op
     p(95.0000) =      2.744 ms/op
     p(99.0000) =      8.384 ms/op
     p(99.9000) =     20.808 ms/op
     p(99.9900) =     21.254 ms/op
     p(99.9990) =     21.529 ms/op
     p(99.9999) =     21.529 ms/op
    p(100.0000) =     21.529 ms/op


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
# Warmup Iteration   1: 3.116 ±(99.9%) 0.076 ms/op
Iteration   1: 1.809 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   0.616 ms/op
                 existUser·p0.50:   1.661 ms/op
                 existUser·p0.90:   2.339 ms/op
                 existUser·p0.95:   2.548 ms/op
                 existUser·p0.99:   2.879 ms/op
                 existUser·p0.999:  13.304 ms/op
                 existUser·p0.9999: 13.783 ms/op
                 existUser·p1.00:   13.795 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17667
  mean =      1.809 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 130 
    [ 1.250,  2.500) = 16471 
    [ 2.500,  3.750) = 1028 
    [ 3.750,  5.000) = 2 
    [ 5.000,  6.250) = 4 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 28 
    [13.750, 15.000) = 4 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.616 ms/op
     p(50.0000) =      1.661 ms/op
     p(90.0000) =      2.339 ms/op
     p(95.0000) =      2.548 ms/op
     p(99.0000) =      2.879 ms/op
     p(99.9000) =     13.304 ms/op
     p(99.9900) =     13.783 ms/op
     p(99.9990) =     13.795 ms/op
     p(99.9999) =     13.795 ms/op
    p(100.0000) =     13.795 ms/op


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
# Warmup Iteration   1: 3.055 ±(99.9%) 0.067 ms/op
Iteration   1: 1.972 ±(99.9%) 0.027 ms/op
                 getUser·p0.00:   0.524 ms/op
                 getUser·p0.50:   1.858 ms/op
                 getUser·p0.90:   2.466 ms/op
                 getUser·p0.95:   2.732 ms/op
                 getUser·p0.99:   4.678 ms/op
                 getUser·p0.999:  19.399 ms/op
                 getUser·p0.9999: 19.464 ms/op
                 getUser·p1.00:   19.464 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16239
  mean =      1.972 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 550 
    [ 1.250,  2.500) = 14180 
    [ 2.500,  3.750) = 1238 
    [ 3.750,  5.000) = 125 
    [ 5.000,  6.250) = 64 
    [ 6.250,  7.500) = 18 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 26 
    [11.250, 12.500) = 6 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.524 ms/op
     p(50.0000) =      1.858 ms/op
     p(90.0000) =      2.466 ms/op
     p(95.0000) =      2.732 ms/op
     p(99.0000) =      4.678 ms/op
     p(99.9000) =     19.399 ms/op
     p(99.9900) =     19.464 ms/op
     p(99.9990) =     19.464 ms/op
     p(99.9999) =     19.464 ms/op
    p(100.0000) =     19.464 ms/op


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
# Warmup Iteration   1: 4.212 ±(99.9%) 0.134 ms/op
Iteration   1: 3.234 ±(99.9%) 0.061 ms/op
                 listUser·p0.00:   1.040 ms/op
                 listUser·p0.50:   3.015 ms/op
                 listUser·p0.90:   3.863 ms/op
                 listUser·p0.95:   4.121 ms/op
                 listUser·p0.99:   6.040 ms/op
                 listUser·p0.999:  33.693 ms/op
                 listUser·p0.9999: 34.669 ms/op
                 listUser·p1.00:   34.669 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9886
  mean =      3.234 ±(99.9%) 0.061 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 431 
    [ 2.500,  5.000) = 9242 
    [ 5.000,  7.500) = 151 
    [ 7.500, 10.000) = 29 
    [10.000, 12.500) = 1 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 31 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.040 ms/op
     p(50.0000) =      3.015 ms/op
     p(90.0000) =      3.863 ms/op
     p(95.0000) =      4.121 ms/op
     p(99.0000) =      6.040 ms/op
     p(99.9000) =     33.693 ms/op
     p(99.9900) =     34.669 ms/op
     p(99.9990) =     34.669 ms/op
     p(99.9999) =     34.669 ms/op
    p(100.0000) =     34.669 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.110          ops/ms
ClientSimple.existUser                       thrpt         16.867          ops/ms
ClientSimple.getUser                         thrpt         13.163          ops/ms
ClientSimple.listUser                        thrpt          8.763          ops/ms
ClientSimple.createUser                       avgt          2.004           ms/op
ClientSimple.existUser                        avgt          1.772           ms/op
ClientSimple.getUser                          avgt          2.056           ms/op
ClientSimple.listUser                         avgt          3.070           ms/op
ClientSimple.createUser                     sample  15227   2.092 ± 0.036   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.460           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.870           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.454           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.744           ms/op
ClientSimple.createUser:createUser·p0.99    sample          8.384           ms/op
ClientSimple.createUser:createUser·p0.999   sample         20.808           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         21.254           ms/op
ClientSimple.createUser:createUser·p1.00    sample         21.529           ms/op
ClientSimple.existUser                      sample  17667   1.809 ± 0.015   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.616           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.661           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.339           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.548           ms/op
ClientSimple.existUser:existUser·p0.99      sample          2.879           ms/op
ClientSimple.existUser:existUser·p0.999     sample         13.304           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         13.783           ms/op
ClientSimple.existUser:existUser·p1.00      sample         13.795           ms/op
ClientSimple.getUser                        sample  16239   1.972 ± 0.027   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.524           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.858           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.466           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.732           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.678           ms/op
ClientSimple.getUser:getUser·p0.999         sample         19.399           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         19.464           ms/op
ClientSimple.getUser:getUser·p1.00          sample         19.464           ms/op
ClientSimple.listUser                       sample   9886   3.234 ± 0.061   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.040           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.015           ms/op
ClientSimple.listUser:listUser·p0.90        sample          3.863           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.121           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.040           ms/op
ClientSimple.listUser:listUser·p0.999       sample         33.693           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         34.669           ms/op
ClientSimple.listUser:listUser·p1.00        sample         34.669           ms/op

Benchmark result is saved to 1710936865065.json
