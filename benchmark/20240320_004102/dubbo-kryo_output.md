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
# Warmup Iteration   1: 0.867 ops/ms
Iteration   1: 6.577 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.577 ops/ms


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
# Warmup Iteration   1: 5.782 ops/ms
Iteration   1: 12.160 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.160 ops/ms


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
# Warmup Iteration   1: 7.025 ops/ms
Iteration   1: 14.317 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  14.317 ops/ms


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
# Warmup Iteration   1: 4.837 ops/ms
Iteration   1: 9.013 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.013 ops/ms


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
# Warmup Iteration   1: 3.857 ±(99.9%) 0.083 ms/op
Iteration   1: 2.118 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.118 ms/op


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
# Warmup Iteration   1: 3.287 ±(99.9%) 0.052 ms/op
Iteration   1: 1.755 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.755 ms/op


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
# Warmup Iteration   1: 3.015 ±(99.9%) 0.051 ms/op
Iteration   1: 2.109 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.109 ms/op


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
# Warmup Iteration   1: 4.827 ±(99.9%) 0.102 ms/op
Iteration   1: 3.501 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.501 ms/op


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
# Warmup Iteration   1: 3.817 ±(99.9%) 0.085 ms/op
Iteration   1: 2.187 ±(99.9%) 0.029 ms/op
                 createUser·p0.00:   0.677 ms/op
                 createUser·p0.50:   1.935 ms/op
                 createUser·p0.90:   2.802 ms/op
                 createUser·p0.95:   3.023 ms/op
                 createUser·p0.99:   5.308 ms/op
                 createUser·p0.999:  15.862 ms/op
                 createUser·p0.9999: 16.705 ms/op
                 createUser·p1.00:   16.761 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14852
  mean =      2.187 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 88 
    [ 1.250,  2.500) = 12232 
    [ 2.500,  3.750) = 2241 
    [ 3.750,  5.000) = 114 
    [ 5.000,  6.250) = 76 
    [ 6.250,  7.500) = 5 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 4 
    [10.000, 11.250) = 22 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 24 
    [13.750, 15.000) = 8 
    [15.000, 16.250) = 34 
    [16.250, 17.500) = 4 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.677 ms/op
     p(50.0000) =      1.935 ms/op
     p(90.0000) =      2.802 ms/op
     p(95.0000) =      3.023 ms/op
     p(99.0000) =      5.308 ms/op
     p(99.9000) =     15.862 ms/op
     p(99.9900) =     16.705 ms/op
     p(99.9990) =     16.761 ms/op
     p(99.9999) =     16.761 ms/op
    p(100.0000) =     16.761 ms/op


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
# Warmup Iteration   1: 3.068 ±(99.9%) 0.066 ms/op
Iteration   1: 1.906 ±(99.9%) 0.027 ms/op
                 existUser·p0.00:   0.240 ms/op
                 existUser·p0.50:   1.774 ms/op
                 existUser·p0.90:   2.298 ms/op
                 existUser·p0.95:   2.560 ms/op
                 existUser·p0.99:   5.486 ms/op
                 existUser·p0.999:  18.093 ms/op
                 existUser·p0.9999: 18.260 ms/op
                 existUser·p1.00:   18.350 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16837
  mean =      1.906 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 614 
    [ 1.250,  2.500) = 15257 
    [ 2.500,  3.750) = 703 
    [ 3.750,  5.000) = 57 
    [ 5.000,  6.250) = 106 
    [ 6.250,  7.500) = 3 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 33 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.240 ms/op
     p(50.0000) =      1.774 ms/op
     p(90.0000) =      2.298 ms/op
     p(95.0000) =      2.560 ms/op
     p(99.0000) =      5.486 ms/op
     p(99.9000) =     18.093 ms/op
     p(99.9900) =     18.260 ms/op
     p(99.9990) =     18.350 ms/op
     p(99.9999) =     18.350 ms/op
    p(100.0000) =     18.350 ms/op


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
# Warmup Iteration   1: 3.444 ±(99.9%) 0.084 ms/op
Iteration   1: 2.140 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   0.632 ms/op
                 getUser·p0.50:   1.849 ms/op
                 getUser·p0.90:   2.929 ms/op
                 getUser·p0.95:   3.138 ms/op
                 getUser·p0.99:   4.638 ms/op
                 getUser·p0.999:  12.567 ms/op
                 getUser·p0.9999: 12.723 ms/op
                 getUser·p1.00:   12.812 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14947
  mean =      2.140 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 94 
    [ 1.250,  2.500) = 10066 
    [ 2.500,  3.750) = 4562 
    [ 3.750,  5.000) = 95 
    [ 5.000,  6.250) = 66 
    [ 6.250,  7.500) = 32 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 13 
    [12.500, 13.750) = 19 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.632 ms/op
     p(50.0000) =      1.849 ms/op
     p(90.0000) =      2.929 ms/op
     p(95.0000) =      3.138 ms/op
     p(99.0000) =      4.638 ms/op
     p(99.9000) =     12.567 ms/op
     p(99.9900) =     12.723 ms/op
     p(99.9990) =     12.812 ms/op
     p(99.9999) =     12.812 ms/op
    p(100.0000) =     12.812 ms/op


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
# Warmup Iteration   1: 4.380 ±(99.9%) 0.139 ms/op
Iteration   1: 3.338 ±(99.9%) 0.031 ms/op
                 listUser·p0.00:   1.221 ms/op
                 listUser·p0.50:   3.305 ms/op
                 listUser·p0.90:   4.121 ms/op
                 listUser·p0.95:   4.507 ms/op
                 listUser·p0.99:   7.350 ms/op
                 listUser·p0.999:  10.221 ms/op
                 listUser·p0.9999: 10.355 ms/op
                 listUser·p1.00:   10.355 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9575
  mean =      3.338 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 1.000,  2.000) = 182 
    [ 2.000,  3.000) = 3394 
    [ 3.000,  4.000) = 4748 
    [ 4.000,  5.000) = 943 
    [ 5.000,  6.000) = 115 
    [ 6.000,  7.000) = 45 
    [ 7.000,  8.000) = 106 
    [ 8.000,  9.000) = 26 
    [ 9.000, 10.000) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.221 ms/op
     p(50.0000) =      3.305 ms/op
     p(90.0000) =      4.121 ms/op
     p(95.0000) =      4.507 ms/op
     p(99.0000) =      7.350 ms/op
     p(99.9000) =     10.221 ms/op
     p(99.9900) =     10.355 ms/op
     p(99.9990) =     10.355 ms/op
     p(99.9999) =     10.355 ms/op
    p(100.0000) =     10.355 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.577          ops/ms
ClientSimple.existUser                       thrpt         12.160          ops/ms
ClientSimple.getUser                         thrpt         14.317          ops/ms
ClientSimple.listUser                        thrpt          9.013          ops/ms
ClientSimple.createUser                       avgt          2.118           ms/op
ClientSimple.existUser                        avgt          1.755           ms/op
ClientSimple.getUser                          avgt          2.109           ms/op
ClientSimple.listUser                         avgt          3.501           ms/op
ClientSimple.createUser                     sample  14852   2.187 ± 0.029   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.677           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.935           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.802           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.023           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.308           ms/op
ClientSimple.createUser:createUser·p0.999   sample         15.862           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         16.705           ms/op
ClientSimple.createUser:createUser·p1.00    sample         16.761           ms/op
ClientSimple.existUser                      sample  16837   1.906 ± 0.027   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.240           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.774           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.298           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.560           ms/op
ClientSimple.existUser:existUser·p0.99      sample          5.486           ms/op
ClientSimple.existUser:existUser·p0.999     sample         18.093           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         18.260           ms/op
ClientSimple.existUser:existUser·p1.00      sample         18.350           ms/op
ClientSimple.getUser                        sample  14947   2.140 ± 0.022   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.632           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.849           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.929           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.138           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.638           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.567           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         12.723           ms/op
ClientSimple.getUser:getUser·p1.00          sample         12.812           ms/op
ClientSimple.listUser                       sample   9575   3.338 ± 0.031   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.221           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.305           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.121           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.507           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.350           ms/op
ClientSimple.listUser:listUser·p0.999       sample         10.221           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         10.355           ms/op
ClientSimple.listUser:listUser·p1.00        sample         10.355           ms/op

Benchmark result is saved to 1710894988098.json
