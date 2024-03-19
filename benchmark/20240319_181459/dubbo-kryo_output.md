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
# Warmup Iteration   1: 1.825 ops/ms
Iteration   1: 7.453 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.453 ops/ms


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
# Warmup Iteration   1: 7.381 ops/ms
Iteration   1: 11.941 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.941 ops/ms


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
# Warmup Iteration   1: 6.238 ops/ms
Iteration   1: 13.893 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.893 ops/ms


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
# Warmup Iteration   1: 4.843 ops/ms
Iteration   1: 8.811 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.811 ops/ms


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
# Warmup Iteration   1: 4.028 ±(99.9%) 0.066 ms/op
Iteration   1: 2.032 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.032 ms/op


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
# Warmup Iteration   1: 3.153 ±(99.9%) 0.047 ms/op
Iteration   1: 1.888 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.888 ms/op


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
# Warmup Iteration   1: 3.331 ±(99.9%) 0.063 ms/op
Iteration   1: 2.256 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.256 ms/op


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
# Warmup Iteration   1: 4.570 ±(99.9%) 0.097 ms/op
Iteration   1: 3.630 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.630 ms/op


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
# Warmup Iteration   1: 3.395 ±(99.9%) 0.092 ms/op
Iteration   1: 2.178 ±(99.9%) 0.045 ms/op
                 createUser·p0.00:   0.740 ms/op
                 createUser·p0.50:   2.009 ms/op
                 createUser·p0.90:   2.638 ms/op
                 createUser·p0.95:   2.826 ms/op
                 createUser·p0.99:   6.029 ms/op
                 createUser·p0.999:  31.130 ms/op
                 createUser·p0.9999: 31.737 ms/op
                 createUser·p1.00:   31.752 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14672
  mean =      2.178 ±(99.9%) 0.045 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12300 
    [ 2.500,  5.000) = 2171 
    [ 5.000,  7.500) = 105 
    [ 7.500, 10.000) = 32 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 20 
    [17.500, 20.000) = 12 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 2 
    [30.000, 32.500) = 30 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.740 ms/op
     p(50.0000) =      2.009 ms/op
     p(90.0000) =      2.638 ms/op
     p(95.0000) =      2.826 ms/op
     p(99.0000) =      6.029 ms/op
     p(99.9000) =     31.130 ms/op
     p(99.9900) =     31.737 ms/op
     p(99.9990) =     31.752 ms/op
     p(99.9999) =     31.752 ms/op
    p(100.0000) =     31.752 ms/op


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
# Warmup Iteration   1: 3.018 ±(99.9%) 0.072 ms/op
Iteration   1: 1.893 ±(99.9%) 0.037 ms/op
                 existUser·p0.00:   0.561 ms/op
                 existUser·p0.50:   1.765 ms/op
                 existUser·p0.90:   2.367 ms/op
                 existUser·p0.95:   2.507 ms/op
                 existUser·p0.99:   3.977 ms/op
                 existUser·p0.999:  31.850 ms/op
                 existUser·p0.9999: 32.178 ms/op
                 existUser·p1.00:   32.178 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16907
  mean =      1.893 ±(99.9%) 0.037 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16047 
    [ 2.500,  5.000) = 780 
    [ 5.000,  7.500) = 12 
    [ 7.500, 10.000) = 3 
    [10.000, 12.500) = 33 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 2 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 30 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.561 ms/op
     p(50.0000) =      1.765 ms/op
     p(90.0000) =      2.367 ms/op
     p(95.0000) =      2.507 ms/op
     p(99.0000) =      3.977 ms/op
     p(99.9000) =     31.850 ms/op
     p(99.9900) =     32.178 ms/op
     p(99.9990) =     32.178 ms/op
     p(99.9999) =     32.178 ms/op
    p(100.0000) =     32.178 ms/op


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
# Warmup Iteration   1: 3.378 ±(99.9%) 0.085 ms/op
Iteration   1: 2.262 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   0.425 ms/op
                 getUser·p0.50:   2.204 ms/op
                 getUser·p0.90:   2.748 ms/op
                 getUser·p0.95:   3.039 ms/op
                 getUser·p0.99:   4.644 ms/op
                 getUser·p0.999:  12.648 ms/op
                 getUser·p0.9999: 13.055 ms/op
                 getUser·p1.00:   13.124 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14160
  mean =      2.262 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 303 
    [ 1.250,  2.500) = 10757 
    [ 2.500,  3.750) = 2791 
    [ 3.750,  5.000) = 178 
    [ 5.000,  6.250) = 67 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 5 
    [ 8.750, 10.000) = 27 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 4 
    [12.500, 13.750) = 28 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.425 ms/op
     p(50.0000) =      2.204 ms/op
     p(90.0000) =      2.748 ms/op
     p(95.0000) =      3.039 ms/op
     p(99.0000) =      4.644 ms/op
     p(99.9000) =     12.648 ms/op
     p(99.9900) =     13.055 ms/op
     p(99.9990) =     13.124 ms/op
     p(99.9999) =     13.124 ms/op
    p(100.0000) =     13.124 ms/op


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
# Warmup Iteration   1: 5.693 ±(99.9%) 0.160 ms/op
Iteration   1: 3.597 ±(99.9%) 0.058 ms/op
                 listUser·p0.00:   1.200 ms/op
                 listUser·p0.50:   3.559 ms/op
                 listUser·p0.90:   4.235 ms/op
                 listUser·p0.95:   4.612 ms/op
                 listUser·p0.99:   7.137 ms/op
                 listUser·p0.999:  27.430 ms/op
                 listUser·p0.9999: 28.180 ms/op
                 listUser·p1.00:   28.180 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8955
  mean =      3.597 ±(99.9%) 0.058 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 832 
    [ 2.500,  5.000) = 7804 
    [ 5.000,  7.500) = 234 
    [ 7.500, 10.000) = 18 
    [10.000, 12.500) = 31 
    [12.500, 15.000) = 4 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 25 

  Percentiles, ms/op:
      p(0.0000) =      1.200 ms/op
     p(50.0000) =      3.559 ms/op
     p(90.0000) =      4.235 ms/op
     p(95.0000) =      4.612 ms/op
     p(99.0000) =      7.137 ms/op
     p(99.9000) =     27.430 ms/op
     p(99.9900) =     28.180 ms/op
     p(99.9990) =     28.180 ms/op
     p(99.9999) =     28.180 ms/op
    p(100.0000) =     28.180 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.453          ops/ms
ClientSimple.existUser                       thrpt         11.941          ops/ms
ClientSimple.getUser                         thrpt         13.893          ops/ms
ClientSimple.listUser                        thrpt          8.811          ops/ms
ClientSimple.createUser                       avgt          2.032           ms/op
ClientSimple.existUser                        avgt          1.888           ms/op
ClientSimple.getUser                          avgt          2.256           ms/op
ClientSimple.listUser                         avgt          3.630           ms/op
ClientSimple.createUser                     sample  14672   2.178 ± 0.045   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.740           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.009           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.638           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.826           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.029           ms/op
ClientSimple.createUser:createUser·p0.999   sample         31.130           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         31.737           ms/op
ClientSimple.createUser:createUser·p1.00    sample         31.752           ms/op
ClientSimple.existUser                      sample  16907   1.893 ± 0.037   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.561           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.765           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.367           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.507           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.977           ms/op
ClientSimple.existUser:existUser·p0.999     sample         31.850           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         32.178           ms/op
ClientSimple.existUser:existUser·p1.00      sample         32.178           ms/op
ClientSimple.getUser                        sample  14160   2.262 ± 0.022   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.425           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.204           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.748           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.039           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.644           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.648           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         13.055           ms/op
ClientSimple.getUser:getUser·p1.00          sample         13.124           ms/op
ClientSimple.listUser                       sample   8955   3.597 ± 0.058   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.200           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.559           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.235           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.612           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.137           ms/op
ClientSimple.listUser:listUser·p0.999       sample         27.430           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         28.180           ms/op
ClientSimple.listUser:listUser·p1.00        sample         28.180           ms/op

Benchmark result is saved to 1710871852717.json
