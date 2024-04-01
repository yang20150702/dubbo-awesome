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
# Warmup Iteration   1: 1.641 ops/ms
Iteration   1: 6.582 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.582 ops/ms


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
# Warmup Iteration   1: 6.752 ops/ms
Iteration   1: 12.833 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.833 ops/ms


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
# Warmup Iteration   1: 5.497 ops/ms
Iteration   1: 13.552 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.552 ops/ms


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
# Warmup Iteration   1: 4.720 ops/ms
Iteration   1: 8.336 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.336 ops/ms


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
# Warmup Iteration   1: 3.671 ±(99.9%) 0.064 ms/op
Iteration   1: 1.960 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  1.960 ms/op


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
# Warmup Iteration   1: 3.273 ±(99.9%) 0.063 ms/op
Iteration   1: 1.803 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.803 ms/op


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
# Warmup Iteration   1: 3.150 ±(99.9%) 0.063 ms/op
Iteration   1: 1.875 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.875 ms/op


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
# Warmup Iteration   1: 4.400 ±(99.9%) 0.076 ms/op
Iteration   1: 3.518 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.518 ms/op


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
# Warmup Iteration   1: 3.557 ±(99.9%) 0.094 ms/op
Iteration   1: 2.107 ±(99.9%) 0.038 ms/op
                 createUser·p0.00:   0.264 ms/op
                 createUser·p0.50:   1.849 ms/op
                 createUser·p0.90:   2.540 ms/op
                 createUser·p0.95:   3.084 ms/op
                 createUser·p0.99:   9.437 ms/op
                 createUser·p0.999:  17.170 ms/op
                 createUser·p0.9999: 17.986 ms/op
                 createUser·p1.00:   18.088 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15170
  mean =      2.107 ±(99.9%) 0.038 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 803 
    [ 1.250,  2.500) = 12762 
    [ 2.500,  3.750) = 1034 
    [ 3.750,  5.000) = 73 
    [ 5.000,  6.250) = 119 
    [ 6.250,  7.500) = 109 
    [ 7.500,  8.750) = 39 
    [ 8.750, 10.000) = 148 
    [10.000, 11.250) = 19 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 16 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 41 
    [17.500, 18.750) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.264 ms/op
     p(50.0000) =      1.849 ms/op
     p(90.0000) =      2.540 ms/op
     p(95.0000) =      3.084 ms/op
     p(99.0000) =      9.437 ms/op
     p(99.9000) =     17.170 ms/op
     p(99.9900) =     17.986 ms/op
     p(99.9990) =     18.088 ms/op
     p(99.9999) =     18.088 ms/op
    p(100.0000) =     18.088 ms/op


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
# Warmup Iteration   1: 3.120 ±(99.9%) 0.069 ms/op
Iteration   1: 2.007 ±(99.9%) 0.027 ms/op
                 existUser·p0.00:   0.605 ms/op
                 existUser·p0.50:   1.841 ms/op
                 existUser·p0.90:   2.478 ms/op
                 existUser·p0.95:   2.687 ms/op
                 existUser·p0.99:   5.022 ms/op
                 existUser·p0.999:  20.974 ms/op
                 existUser·p0.9999: 21.424 ms/op
                 existUser·p1.00:   21.463 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15934
  mean =      2.007 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14453 
    [ 2.500,  5.000) = 1313 
    [ 5.000,  7.500) = 105 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.605 ms/op
     p(50.0000) =      1.841 ms/op
     p(90.0000) =      2.478 ms/op
     p(95.0000) =      2.687 ms/op
     p(99.0000) =      5.022 ms/op
     p(99.9000) =     20.974 ms/op
     p(99.9900) =     21.424 ms/op
     p(99.9990) =     21.463 ms/op
     p(99.9999) =     21.463 ms/op
    p(100.0000) =     21.463 ms/op


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
# Warmup Iteration   1: 3.572 ±(99.9%) 0.092 ms/op
Iteration   1: 1.974 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   0.780 ms/op
                 getUser·p0.50:   1.866 ms/op
                 getUser·p0.90:   2.433 ms/op
                 getUser·p0.95:   2.597 ms/op
                 getUser·p0.99:   3.035 ms/op
                 getUser·p0.999:  15.889 ms/op
                 getUser·p0.9999: 15.970 ms/op
                 getUser·p1.00:   15.991 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16195
  mean =      1.974 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 46 
    [ 1.250,  2.500) = 14936 
    [ 2.500,  3.750) = 1138 
    [ 3.750,  5.000) = 7 
    [ 5.000,  6.250) = 6 
    [ 6.250,  7.500) = 30 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 32 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.780 ms/op
     p(50.0000) =      1.866 ms/op
     p(90.0000) =      2.433 ms/op
     p(95.0000) =      2.597 ms/op
     p(99.0000) =      3.035 ms/op
     p(99.9000) =     15.889 ms/op
     p(99.9900) =     15.970 ms/op
     p(99.9990) =     15.991 ms/op
     p(99.9999) =     15.991 ms/op
    p(100.0000) =     15.991 ms/op


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
# Warmup Iteration   1: 4.586 ±(99.9%) 0.168 ms/op
Iteration   1: 3.312 ±(99.9%) 0.053 ms/op
                 listUser·p0.00:   0.988 ms/op
                 listUser·p0.50:   3.019 ms/op
                 listUser·p0.90:   4.063 ms/op
                 listUser·p0.95:   4.383 ms/op
                 listUser·p0.99:   5.603 ms/op
                 listUser·p0.999:  27.788 ms/op
                 listUser·p0.9999: 29.229 ms/op
                 listUser·p1.00:   29.229 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9658
  mean =      3.312 ±(99.9%) 0.053 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 340 
    [ 2.500,  5.000) = 9130 
    [ 5.000,  7.500) = 124 
    [ 7.500, 10.000) = 13 
    [10.000, 12.500) = 17 
    [12.500, 15.000) = 2 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 21 

  Percentiles, ms/op:
      p(0.0000) =      0.988 ms/op
     p(50.0000) =      3.019 ms/op
     p(90.0000) =      4.063 ms/op
     p(95.0000) =      4.383 ms/op
     p(99.0000) =      5.603 ms/op
     p(99.9000) =     27.788 ms/op
     p(99.9900) =     29.229 ms/op
     p(99.9990) =     29.229 ms/op
     p(99.9999) =     29.229 ms/op
    p(100.0000) =     29.229 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.582          ops/ms
ClientSimple.existUser                       thrpt         12.833          ops/ms
ClientSimple.getUser                         thrpt         13.552          ops/ms
ClientSimple.listUser                        thrpt          8.336          ops/ms
ClientSimple.createUser                       avgt          1.960           ms/op
ClientSimple.existUser                        avgt          1.803           ms/op
ClientSimple.getUser                          avgt          1.875           ms/op
ClientSimple.listUser                         avgt          3.518           ms/op
ClientSimple.createUser                     sample  15170   2.107 ± 0.038   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.264           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.849           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.540           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.084           ms/op
ClientSimple.createUser:createUser·p0.99    sample          9.437           ms/op
ClientSimple.createUser:createUser·p0.999   sample         17.170           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         17.986           ms/op
ClientSimple.createUser:createUser·p1.00    sample         18.088           ms/op
ClientSimple.existUser                      sample  15934   2.007 ± 0.027   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.605           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.841           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.478           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.687           ms/op
ClientSimple.existUser:existUser·p0.99      sample          5.022           ms/op
ClientSimple.existUser:existUser·p0.999     sample         20.974           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         21.424           ms/op
ClientSimple.existUser:existUser·p1.00      sample         21.463           ms/op
ClientSimple.getUser                        sample  16195   1.974 ± 0.019   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.780           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.866           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.433           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.597           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.035           ms/op
ClientSimple.getUser:getUser·p0.999         sample         15.889           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         15.970           ms/op
ClientSimple.getUser:getUser·p1.00          sample         15.991           ms/op
ClientSimple.listUser                       sample   9658   3.312 ± 0.053   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.988           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.019           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.063           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.383           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.603           ms/op
ClientSimple.listUser:listUser·p0.999       sample         27.788           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         29.229           ms/op
ClientSimple.listUser:listUser·p1.00        sample         29.229           ms/op

Benchmark result is saved to 1711932084961.json
