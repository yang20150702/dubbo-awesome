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
# Warmup Iteration   1: 1.677 ops/ms
Iteration   1: 6.567 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.567 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:19
# Fork: 1 of 1
# Warmup Iteration   1: 6.370 ops/ms
Iteration   1: 11.567 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.567 ops/ms


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
# Warmup Iteration   1: 6.102 ops/ms
Iteration   1: 12.921 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.921 ops/ms


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
# Warmup Iteration   1: 4.409 ops/ms
Iteration   1: 7.916 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  7.916 ops/ms


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
# Warmup Iteration   1: 3.912 ±(99.9%) 0.069 ms/op
Iteration   1: 2.102 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.102 ms/op


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
# Warmup Iteration   1: 3.144 ±(99.9%) 0.049 ms/op
Iteration   1: 1.921 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.921 ms/op


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
# Warmup Iteration   1: 3.659 ±(99.9%) 0.063 ms/op
Iteration   1: 2.052 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.052 ms/op


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
# Warmup Iteration   1: 4.587 ±(99.9%) 0.079 ms/op
Iteration   1: 3.686 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.686 ms/op


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
# Warmup Iteration   1: 3.658 ±(99.9%) 0.090 ms/op
Iteration   1: 2.233 ±(99.9%) 0.041 ms/op
                 createUser·p0.00:   0.539 ms/op
                 createUser·p0.50:   1.923 ms/op
                 createUser·p0.90:   2.830 ms/op
                 createUser·p0.95:   3.080 ms/op
                 createUser·p0.99:   12.665 ms/op
                 createUser·p0.999:  16.717 ms/op
                 createUser·p0.9999: 21.561 ms/op
                 createUser·p1.00:   21.561 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14694
  mean =      2.233 ±(99.9%) 0.041 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11372 
    [ 2.500,  5.000) = 2986 
    [ 5.000,  7.500) = 126 
    [ 7.500, 10.000) = 50 
    [10.000, 12.500) = 7 
    [12.500, 15.000) = 103 
    [15.000, 17.500) = 41 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.539 ms/op
     p(50.0000) =      1.923 ms/op
     p(90.0000) =      2.830 ms/op
     p(95.0000) =      3.080 ms/op
     p(99.0000) =     12.665 ms/op
     p(99.9000) =     16.717 ms/op
     p(99.9900) =     21.561 ms/op
     p(99.9990) =     21.561 ms/op
     p(99.9999) =     21.561 ms/op
    p(100.0000) =     21.561 ms/op


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
# Warmup Iteration   1: 2.985 ±(99.9%) 0.074 ms/op
Iteration   1: 1.956 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   0.623 ms/op
                 existUser·p0.50:   1.880 ms/op
                 existUser·p0.90:   2.425 ms/op
                 existUser·p0.95:   2.564 ms/op
                 existUser·p0.99:   3.559 ms/op
                 existUser·p0.999:  11.109 ms/op
                 existUser·p0.9999: 12.036 ms/op
                 existUser·p1.00:   12.173 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16468
  mean =      1.956 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 431 
    [ 1.250,  2.500) = 14888 
    [ 2.500,  3.750) = 1012 
    [ 3.750,  5.000) = 39 
    [ 5.000,  6.250) = 3 
    [ 6.250,  7.500) = 24 
    [ 7.500,  8.750) = 28 
    [ 8.750, 10.000) = 10 
    [10.000, 11.250) = 19 
    [11.250, 12.500) = 14 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.623 ms/op
     p(50.0000) =      1.880 ms/op
     p(90.0000) =      2.425 ms/op
     p(95.0000) =      2.564 ms/op
     p(99.0000) =      3.559 ms/op
     p(99.9000) =     11.109 ms/op
     p(99.9900) =     12.036 ms/op
     p(99.9990) =     12.173 ms/op
     p(99.9999) =     12.173 ms/op
    p(100.0000) =     12.173 ms/op


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
# Warmup Iteration   1: 3.165 ±(99.9%) 0.074 ms/op
Iteration   1: 2.015 ±(99.9%) 0.039 ms/op
                 getUser·p0.00:   0.625 ms/op
                 getUser·p0.50:   1.806 ms/op
                 getUser·p0.90:   2.511 ms/op
                 getUser·p0.95:   2.793 ms/op
                 getUser·p0.99:   5.390 ms/op
                 getUser·p0.999:  23.921 ms/op
                 getUser·p0.9999: 32.594 ms/op
                 getUser·p1.00:   32.768 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15892
  mean =      2.015 ±(99.9%) 0.039 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14247 
    [ 2.500,  5.000) = 1454 
    [ 5.000,  7.500) = 75 
    [ 7.500, 10.000) = 16 
    [10.000, 12.500) = 7 
    [12.500, 15.000) = 24 
    [15.000, 17.500) = 5 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.625 ms/op
     p(50.0000) =      1.806 ms/op
     p(90.0000) =      2.511 ms/op
     p(95.0000) =      2.793 ms/op
     p(99.0000) =      5.390 ms/op
     p(99.9000) =     23.921 ms/op
     p(99.9900) =     32.594 ms/op
     p(99.9990) =     32.768 ms/op
     p(99.9999) =     32.768 ms/op
    p(100.0000) =     32.768 ms/op


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
# Warmup Iteration   1: 4.494 ±(99.9%) 0.129 ms/op
Iteration   1: 3.455 ±(99.9%) 0.039 ms/op
                 listUser·p0.00:   0.891 ms/op
                 listUser·p0.50:   3.314 ms/op
                 listUser·p0.90:   4.293 ms/op
                 listUser·p0.95:   4.579 ms/op
                 listUser·p0.99:   6.671 ms/op
                 listUser·p0.999:  16.220 ms/op
                 listUser·p0.9999: 16.761 ms/op
                 listUser·p1.00:   16.761 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9270
  mean =      3.455 ±(99.9%) 0.039 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 5 
    [ 1.250,  2.500) = 696 
    [ 2.500,  3.750) = 5726 
    [ 3.750,  5.000) = 2548 
    [ 5.000,  6.250) = 169 
    [ 6.250,  7.500) = 49 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 34 
    [10.000, 11.250) = 9 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 26 
    [16.250, 17.500) = 6 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.891 ms/op
     p(50.0000) =      3.314 ms/op
     p(90.0000) =      4.293 ms/op
     p(95.0000) =      4.579 ms/op
     p(99.0000) =      6.671 ms/op
     p(99.9000) =     16.220 ms/op
     p(99.9900) =     16.761 ms/op
     p(99.9990) =     16.761 ms/op
     p(99.9999) =     16.761 ms/op
    p(100.0000) =     16.761 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.567          ops/ms
ClientSimple.existUser                       thrpt         11.567          ops/ms
ClientSimple.getUser                         thrpt         12.921          ops/ms
ClientSimple.listUser                        thrpt          7.916          ops/ms
ClientSimple.createUser                       avgt          2.102           ms/op
ClientSimple.existUser                        avgt          1.921           ms/op
ClientSimple.getUser                          avgt          2.052           ms/op
ClientSimple.listUser                         avgt          3.686           ms/op
ClientSimple.createUser                     sample  14694   2.233 ± 0.041   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.539           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.923           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.830           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.080           ms/op
ClientSimple.createUser:createUser·p0.99    sample         12.665           ms/op
ClientSimple.createUser:createUser·p0.999   sample         16.717           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         21.561           ms/op
ClientSimple.createUser:createUser·p1.00    sample         21.561           ms/op
ClientSimple.existUser                      sample  16468   1.956 ± 0.018   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.623           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.880           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.425           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.564           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.559           ms/op
ClientSimple.existUser:existUser·p0.999     sample         11.109           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         12.036           ms/op
ClientSimple.existUser:existUser·p1.00      sample         12.173           ms/op
ClientSimple.getUser                        sample  15892   2.015 ± 0.039   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.625           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.806           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.511           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.793           ms/op
ClientSimple.getUser:getUser·p0.99          sample          5.390           ms/op
ClientSimple.getUser:getUser·p0.999         sample         23.921           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         32.594           ms/op
ClientSimple.getUser:getUser·p1.00          sample         32.768           ms/op
ClientSimple.listUser                       sample   9270   3.455 ± 0.039   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.891           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.314           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.293           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.579           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.671           ms/op
ClientSimple.listUser:listUser·p0.999       sample         16.220           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         16.761           ms/op
ClientSimple.listUser:listUser·p1.00        sample         16.761           ms/op

Benchmark result is saved to 1712146485351.json
