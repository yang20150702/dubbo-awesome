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
# Warmup Iteration   1: 1.085 ops/ms
Iteration   1: 6.793 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.793 ops/ms


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
# Warmup Iteration   1: 6.238 ops/ms
Iteration   1: 12.882 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.882 ops/ms


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
# Warmup Iteration   1: 5.494 ops/ms
Iteration   1: 12.779 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.779 ops/ms


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
# Warmup Iteration   1: 4.538 ops/ms
Iteration   1: 8.011 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.011 ops/ms


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
# Warmup Iteration   1: 3.738 ±(99.9%) 0.066 ms/op
Iteration   1: 2.058 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.058 ms/op


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
# Warmup Iteration   1: 3.342 ±(99.9%) 0.070 ms/op
Iteration   1: 1.724 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.724 ms/op


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
# Warmup Iteration   1: 3.191 ±(99.9%) 0.059 ms/op
Iteration   1: 1.928 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.928 ms/op


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
# Warmup Iteration   1: 5.465 ±(99.9%) 0.117 ms/op
Iteration   1: 3.757 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.757 ms/op


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
# Warmup Iteration   1: 3.494 ±(99.9%) 0.083 ms/op
Iteration   1: 2.024 ±(99.9%) 0.037 ms/op
                 createUser·p0.00:   0.767 ms/op
                 createUser·p0.50:   1.792 ms/op
                 createUser·p0.90:   2.367 ms/op
                 createUser·p0.95:   2.589 ms/op
                 createUser·p0.99:   10.222 ms/op
                 createUser·p0.999:  19.792 ms/op
                 createUser·p0.9999: 21.222 ms/op
                 createUser·p1.00:   21.299 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15851
  mean =      2.024 ±(99.9%) 0.037 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14825 
    [ 2.500,  5.000) = 783 
    [ 5.000,  7.500) = 65 
    [ 7.500, 10.000) = 18 
    [10.000, 12.500) = 82 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 38 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.767 ms/op
     p(50.0000) =      1.792 ms/op
     p(90.0000) =      2.367 ms/op
     p(95.0000) =      2.589 ms/op
     p(99.0000) =     10.222 ms/op
     p(99.9000) =     19.792 ms/op
     p(99.9900) =     21.222 ms/op
     p(99.9990) =     21.299 ms/op
     p(99.9999) =     21.299 ms/op
    p(100.0000) =     21.299 ms/op


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
# Warmup Iteration   1: 3.282 ±(99.9%) 0.103 ms/op
Iteration   1: 1.833 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   0.774 ms/op
                 existUser·p0.50:   1.671 ms/op
                 existUser·p0.90:   2.318 ms/op
                 existUser·p0.95:   2.576 ms/op
                 existUser·p0.99:   4.235 ms/op
                 existUser·p0.999:  14.254 ms/op
                 existUser·p0.9999: 14.582 ms/op
                 existUser·p1.00:   14.680 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17447
  mean =      1.833 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 247 
    [ 1.250,  2.500) = 16099 
    [ 2.500,  3.750) = 885 
    [ 3.750,  5.000) = 71 
    [ 5.000,  6.250) = 67 
    [ 6.250,  7.500) = 23 
    [ 7.500,  8.750) = 12 
    [ 8.750, 10.000) = 10 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 3 
    [13.750, 15.000) = 29 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.774 ms/op
     p(50.0000) =      1.671 ms/op
     p(90.0000) =      2.318 ms/op
     p(95.0000) =      2.576 ms/op
     p(99.0000) =      4.235 ms/op
     p(99.9000) =     14.254 ms/op
     p(99.9900) =     14.582 ms/op
     p(99.9990) =     14.680 ms/op
     p(99.9999) =     14.680 ms/op
    p(100.0000) =     14.680 ms/op


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
# Warmup Iteration   1: 3.121 ±(99.9%) 0.085 ms/op
Iteration   1: 1.906 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   0.933 ms/op
                 getUser·p0.50:   1.786 ms/op
                 getUser·p0.90:   2.404 ms/op
                 getUser·p0.95:   2.707 ms/op
                 getUser·p0.99:   3.957 ms/op
                 getUser·p0.999:  13.619 ms/op
                 getUser·p0.9999: 13.745 ms/op
                 getUser·p1.00:   13.844 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16772
  mean =      1.906 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 173 
    [ 1.250,  2.500) = 15256 
    [ 2.500,  3.750) = 1136 
    [ 3.750,  5.000) = 134 
    [ 5.000,  6.250) = 41 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 31 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.933 ms/op
     p(50.0000) =      1.786 ms/op
     p(90.0000) =      2.404 ms/op
     p(95.0000) =      2.707 ms/op
     p(99.0000) =      3.957 ms/op
     p(99.9000) =     13.619 ms/op
     p(99.9900) =     13.745 ms/op
     p(99.9990) =     13.844 ms/op
     p(99.9999) =     13.844 ms/op
    p(100.0000) =     13.844 ms/op


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
# Warmup Iteration   1: 4.654 ±(99.9%) 0.155 ms/op
Iteration   1: 3.406 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   1.033 ms/op
                 listUser·p0.50:   3.314 ms/op
                 listUser·p0.90:   4.211 ms/op
                 listUser·p0.95:   4.432 ms/op
                 listUser·p0.99:   5.603 ms/op
                 listUser·p0.999:  7.586 ms/op
                 listUser·p0.9999: 7.995 ms/op
                 listUser·p1.00:   7.995 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9379
  mean =      3.406 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [1.000, 1.500) = 23 
    [1.500, 2.000) = 221 
    [2.000, 2.500) = 390 
    [2.500, 3.000) = 2081 
    [3.000, 3.500) = 2790 
    [3.500, 4.000) = 2207 
    [4.000, 4.500) = 1251 
    [4.500, 5.000) = 220 
    [5.000, 5.500) = 91 
    [5.500, 6.000) = 52 
    [6.000, 6.500) = 14 
    [6.500, 7.000) = 14 
    [7.000, 7.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      1.033 ms/op
     p(50.0000) =      3.314 ms/op
     p(90.0000) =      4.211 ms/op
     p(95.0000) =      4.432 ms/op
     p(99.0000) =      5.603 ms/op
     p(99.9000) =      7.586 ms/op
     p(99.9900) =      7.995 ms/op
     p(99.9990) =      7.995 ms/op
     p(99.9999) =      7.995 ms/op
    p(100.0000) =      7.995 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.793          ops/ms
ClientSimple.existUser                       thrpt         12.882          ops/ms
ClientSimple.getUser                         thrpt         12.779          ops/ms
ClientSimple.listUser                        thrpt          8.011          ops/ms
ClientSimple.createUser                       avgt          2.058           ms/op
ClientSimple.existUser                        avgt          1.724           ms/op
ClientSimple.getUser                          avgt          1.928           ms/op
ClientSimple.listUser                         avgt          3.757           ms/op
ClientSimple.createUser                     sample  15851   2.024 ± 0.037   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.767           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.792           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.367           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.589           ms/op
ClientSimple.createUser:createUser·p0.99    sample         10.222           ms/op
ClientSimple.createUser:createUser·p0.999   sample         19.792           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         21.222           ms/op
ClientSimple.createUser:createUser·p1.00    sample         21.299           ms/op
ClientSimple.existUser                      sample  17447   1.833 ± 0.019   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.774           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.671           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.318           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.576           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.235           ms/op
ClientSimple.existUser:existUser·p0.999     sample         14.254           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         14.582           ms/op
ClientSimple.existUser:existUser·p1.00      sample         14.680           ms/op
ClientSimple.getUser                        sample  16772   1.906 ± 0.018   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.933           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.786           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.404           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.707           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.957           ms/op
ClientSimple.getUser:getUser·p0.999         sample         13.619           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         13.745           ms/op
ClientSimple.getUser:getUser·p1.00          sample         13.844           ms/op
ClientSimple.listUser                       sample   9379   3.406 ± 0.024   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.033           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.314           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.211           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.432           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.603           ms/op
ClientSimple.listUser:listUser·p0.999       sample          7.586           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          7.995           ms/op
ClientSimple.listUser:listUser·p1.00        sample          7.995           ms/op

Benchmark result is saved to 1712104618956.json
