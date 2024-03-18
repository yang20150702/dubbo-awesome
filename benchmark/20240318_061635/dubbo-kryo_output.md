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
# Warmup Iteration   1: 1.708 ops/ms
Iteration   1: 6.938 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.938 ops/ms


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
# Warmup Iteration   1: 5.926 ops/ms
Iteration   1: 13.121 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.121 ops/ms


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
# Warmup Iteration   1: 5.551 ops/ms
Iteration   1: 11.524 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.524 ops/ms


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
# Warmup Iteration   1: 4.623 ops/ms
Iteration   1: 8.957 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.957 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.567 ±(99.9%) 0.056 ms/op
Iteration   1: 2.099 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.099 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.046 ±(99.9%) 0.048 ms/op
Iteration   1: 1.647 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.647 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.127 ±(99.9%) 0.051 ms/op
Iteration   1: 1.817 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.817 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 4.467 ±(99.9%) 0.092 ms/op
Iteration   1: 3.770 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.770 ms/op


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
# Warmup Iteration   1: 3.379 ±(99.9%) 0.093 ms/op
Iteration   1: 2.038 ±(99.9%) 0.026 ms/op
                 createUser·p0.00:   0.804 ms/op
                 createUser·p0.50:   1.911 ms/op
                 createUser·p0.90:   2.363 ms/op
                 createUser·p0.95:   2.654 ms/op
                 createUser·p0.99:   5.246 ms/op
                 createUser·p0.999:  20.349 ms/op
                 createUser·p0.9999: 21.449 ms/op
                 createUser·p1.00:   21.529 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 16105
  mean =      2.038 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14988 
    [ 2.500,  5.000) = 939 
    [ 5.000,  7.500) = 141 
    [ 7.500, 10.000) = 5 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.804 ms/op
     p(50.0000) =      1.911 ms/op
     p(90.0000) =      2.363 ms/op
     p(95.0000) =      2.654 ms/op
     p(99.0000) =      5.246 ms/op
     p(99.9000) =     20.349 ms/op
     p(99.9900) =     21.449 ms/op
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
# Warmup Iteration   1: 2.990 ±(99.9%) 0.067 ms/op
Iteration   1: 1.859 ±(99.9%) 0.033 ms/op
                 existUser·p0.00:   0.581 ms/op
                 existUser·p0.50:   1.743 ms/op
                 existUser·p0.90:   2.200 ms/op
                 existUser·p0.95:   2.355 ms/op
                 existUser·p0.99:   2.916 ms/op
                 existUser·p0.999:  29.360 ms/op
                 existUser·p0.9999: 29.892 ms/op
                 existUser·p1.00:   30.081 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17208
  mean =      1.859 ±(99.9%) 0.033 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16702 
    [ 2.500,  5.000) = 401 
    [ 5.000,  7.500) = 41 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 31 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.581 ms/op
     p(50.0000) =      1.743 ms/op
     p(90.0000) =      2.200 ms/op
     p(95.0000) =      2.355 ms/op
     p(99.0000) =      2.916 ms/op
     p(99.9000) =     29.360 ms/op
     p(99.9900) =     29.892 ms/op
     p(99.9990) =     30.081 ms/op
     p(99.9999) =     30.081 ms/op
    p(100.0000) =     30.081 ms/op


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
# Warmup Iteration   1: 3.020 ±(99.9%) 0.069 ms/op
Iteration   1: 2.007 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   0.405 ms/op
                 getUser·p0.50:   1.886 ms/op
                 getUser·p0.90:   2.605 ms/op
                 getUser·p0.95:   2.847 ms/op
                 getUser·p0.99:   3.863 ms/op
                 getUser·p0.999:  13.140 ms/op
                 getUser·p0.9999: 13.398 ms/op
                 getUser·p1.00:   13.631 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15925
  mean =      2.007 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 251 
    [ 1.250,  2.500) = 13187 
    [ 2.500,  3.750) = 2309 
    [ 3.750,  5.000) = 80 
    [ 5.000,  6.250) = 66 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.405 ms/op
     p(50.0000) =      1.886 ms/op
     p(90.0000) =      2.605 ms/op
     p(95.0000) =      2.847 ms/op
     p(99.0000) =      3.863 ms/op
     p(99.9000) =     13.140 ms/op
     p(99.9900) =     13.398 ms/op
     p(99.9990) =     13.631 ms/op
     p(99.9999) =     13.631 ms/op
    p(100.0000) =     13.631 ms/op


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
# Warmup Iteration   1: 4.481 ±(99.9%) 0.128 ms/op
Iteration   1: 3.141 ±(99.9%) 0.040 ms/op
                 listUser·p0.00:   1.096 ms/op
                 listUser·p0.50:   2.855 ms/op
                 listUser·p0.90:   3.838 ms/op
                 listUser·p0.95:   4.186 ms/op
                 listUser·p0.99:   6.578 ms/op
                 listUser·p0.999:  19.843 ms/op
                 listUser·p0.9999: 20.577 ms/op
                 listUser·p1.00:   20.578 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10224
  mean =      3.141 ±(99.9%) 0.040 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 567 
    [ 2.500,  5.000) = 9419 
    [ 5.000,  7.500) = 164 
    [ 7.500, 10.000) = 10 
    [10.000, 12.500) = 31 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.096 ms/op
     p(50.0000) =      2.855 ms/op
     p(90.0000) =      3.838 ms/op
     p(95.0000) =      4.186 ms/op
     p(99.0000) =      6.578 ms/op
     p(99.9000) =     19.843 ms/op
     p(99.9900) =     20.577 ms/op
     p(99.9990) =     20.578 ms/op
     p(99.9999) =     20.578 ms/op
    p(100.0000) =     20.578 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.938          ops/ms
ClientSimple.existUser                       thrpt         13.121          ops/ms
ClientSimple.getUser                         thrpt         11.524          ops/ms
ClientSimple.listUser                        thrpt          8.957          ops/ms
ClientSimple.createUser                       avgt          2.099           ms/op
ClientSimple.existUser                        avgt          1.647           ms/op
ClientSimple.getUser                          avgt          1.817           ms/op
ClientSimple.listUser                         avgt          3.770           ms/op
ClientSimple.createUser                     sample  16105   2.038 ± 0.026   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.804           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.911           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.363           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.654           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.246           ms/op
ClientSimple.createUser:createUser·p0.999   sample         20.349           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         21.449           ms/op
ClientSimple.createUser:createUser·p1.00    sample         21.529           ms/op
ClientSimple.existUser                      sample  17208   1.859 ± 0.033   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.581           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.743           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.200           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.355           ms/op
ClientSimple.existUser:existUser·p0.99      sample          2.916           ms/op
ClientSimple.existUser:existUser·p0.999     sample         29.360           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         29.892           ms/op
ClientSimple.existUser:existUser·p1.00      sample         30.081           ms/op
ClientSimple.getUser                        sample  15925   2.007 ± 0.019   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.405           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.886           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.605           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.847           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.863           ms/op
ClientSimple.getUser:getUser·p0.999         sample         13.140           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         13.398           ms/op
ClientSimple.getUser:getUser·p1.00          sample         13.631           ms/op
ClientSimple.listUser                       sample  10224   3.141 ± 0.040   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.096           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.855           ms/op
ClientSimple.listUser:listUser·p0.90        sample          3.838           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.186           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.578           ms/op
ClientSimple.listUser:listUser·p0.999       sample         19.843           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         20.577           ms/op
ClientSimple.listUser:listUser·p1.00        sample         20.578           ms/op

Benchmark result is saved to 1710742321100.json
