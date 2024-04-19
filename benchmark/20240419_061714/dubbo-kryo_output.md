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
# Warmup Iteration   1: 1.735 ops/ms
Iteration   1: 7.321 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.321 ops/ms


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
# Warmup Iteration   1: 5.123 ops/ms
Iteration   1: 10.308 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  10.308 ops/ms


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
# Warmup Iteration   1: 4.735 ops/ms
Iteration   1: 11.362 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.362 ops/ms


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
# Warmup Iteration   1: 4.595 ops/ms
Iteration   1: 7.706 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  7.706 ops/ms


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
# Warmup Iteration   1: 4.246 ±(99.9%) 0.086 ms/op
Iteration   1: 2.296 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.296 ms/op


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
# Warmup Iteration   1: 3.224 ±(99.9%) 0.054 ms/op
Iteration   1: 2.074 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.074 ms/op


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
# Warmup Iteration   1: 3.239 ±(99.9%) 0.059 ms/op
Iteration   1: 1.932 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.932 ms/op


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
# Warmup Iteration   1: 4.864 ±(99.9%) 0.081 ms/op
Iteration   1: 3.635 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.635 ms/op


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
# Warmup Iteration   1: 3.832 ±(99.9%) 0.094 ms/op
Iteration   1: 2.208 ±(99.9%) 0.038 ms/op
                 createUser·p0.00:   0.490 ms/op
                 createUser·p0.50:   2.028 ms/op
                 createUser·p0.90:   2.724 ms/op
                 createUser·p0.95:   3.166 ms/op
                 createUser·p0.99:   8.275 ms/op
                 createUser·p0.999:  19.431 ms/op
                 createUser·p0.9999: 20.119 ms/op
                 createUser·p1.00:   20.251 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14463
  mean =      2.208 ±(99.9%) 0.038 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11619 
    [ 2.500,  5.000) = 2618 
    [ 5.000,  7.500) = 58 
    [ 7.500, 10.000) = 37 
    [10.000, 12.500) = 45 
    [12.500, 15.000) = 41 
    [15.000, 17.500) = 14 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.490 ms/op
     p(50.0000) =      2.028 ms/op
     p(90.0000) =      2.724 ms/op
     p(95.0000) =      3.166 ms/op
     p(99.0000) =      8.275 ms/op
     p(99.9000) =     19.431 ms/op
     p(99.9900) =     20.119 ms/op
     p(99.9990) =     20.251 ms/op
     p(99.9999) =     20.251 ms/op
    p(100.0000) =     20.251 ms/op


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
# Warmup Iteration   1: 2.918 ±(99.9%) 0.083 ms/op
Iteration   1: 1.743 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   0.606 ms/op
                 existUser·p0.50:   1.647 ms/op
                 existUser·p0.90:   2.089 ms/op
                 existUser·p0.95:   2.318 ms/op
                 existUser·p0.99:   3.470 ms/op
                 existUser·p0.999:  12.503 ms/op
                 existUser·p0.9999: 13.517 ms/op
                 existUser·p1.00:   13.517 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 18445
  mean =      1.743 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 533 
    [ 1.250,  2.500) = 17245 
    [ 2.500,  3.750) = 496 
    [ 3.750,  5.000) = 104 
    [ 5.000,  6.250) = 3 
    [ 6.250,  7.500) = 14 
    [ 7.500,  8.750) = 18 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 14 
    [12.500, 13.750) = 18 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.606 ms/op
     p(50.0000) =      1.647 ms/op
     p(90.0000) =      2.089 ms/op
     p(95.0000) =      2.318 ms/op
     p(99.0000) =      3.470 ms/op
     p(99.9000) =     12.503 ms/op
     p(99.9900) =     13.517 ms/op
     p(99.9990) =     13.517 ms/op
     p(99.9999) =     13.517 ms/op
    p(100.0000) =     13.517 ms/op


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
# Warmup Iteration   1: 3.719 ±(99.9%) 0.098 ms/op
Iteration   1: 2.087 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   0.748 ms/op
                 getUser·p0.50:   1.972 ms/op
                 getUser·p0.90:   2.564 ms/op
                 getUser·p0.95:   2.847 ms/op
                 getUser·p0.99:   4.620 ms/op
                 getUser·p0.999:  11.889 ms/op
                 getUser·p0.9999: 12.705 ms/op
                 getUser·p1.00:   12.714 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15349
  mean =      2.087 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 40 
    [ 1.250,  2.500) = 13491 
    [ 2.500,  3.750) = 1625 
    [ 3.750,  5.000) = 82 
    [ 5.000,  6.250) = 47 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 31 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 24 
    [12.500, 13.750) = 9 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.748 ms/op
     p(50.0000) =      1.972 ms/op
     p(90.0000) =      2.564 ms/op
     p(95.0000) =      2.847 ms/op
     p(99.0000) =      4.620 ms/op
     p(99.9000) =     11.889 ms/op
     p(99.9900) =     12.705 ms/op
     p(99.9990) =     12.714 ms/op
     p(99.9999) =     12.714 ms/op
    p(100.0000) =     12.714 ms/op


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
# Warmup Iteration   1: 4.287 ±(99.9%) 0.119 ms/op
Iteration   1: 3.712 ±(99.9%) 0.066 ms/op
                 listUser·p0.00:   0.788 ms/op
                 listUser·p0.50:   3.690 ms/op
                 listUser·p0.90:   4.571 ms/op
                 listUser·p0.95:   4.899 ms/op
                 listUser·p0.99:   8.895 ms/op
                 listUser·p0.999:  28.390 ms/op
                 listUser·p0.9999: 29.032 ms/op
                 listUser·p1.00:   29.032 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8610
  mean =      3.712 ±(99.9%) 0.066 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 936 
    [ 2.500,  5.000) = 7326 
    [ 5.000,  7.500) = 215 
    [ 7.500, 10.000) = 69 
    [10.000, 12.500) = 24 
    [12.500, 15.000) = 8 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.788 ms/op
     p(50.0000) =      3.690 ms/op
     p(90.0000) =      4.571 ms/op
     p(95.0000) =      4.899 ms/op
     p(99.0000) =      8.895 ms/op
     p(99.9000) =     28.390 ms/op
     p(99.9900) =     29.032 ms/op
     p(99.9990) =     29.032 ms/op
     p(99.9999) =     29.032 ms/op
    p(100.0000) =     29.032 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.321          ops/ms
ClientSimple.existUser                       thrpt         10.308          ops/ms
ClientSimple.getUser                         thrpt         11.362          ops/ms
ClientSimple.listUser                        thrpt          7.706          ops/ms
ClientSimple.createUser                       avgt          2.296           ms/op
ClientSimple.existUser                        avgt          2.074           ms/op
ClientSimple.getUser                          avgt          1.932           ms/op
ClientSimple.listUser                         avgt          3.635           ms/op
ClientSimple.createUser                     sample  14463   2.208 ± 0.038   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.490           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.028           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.724           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.166           ms/op
ClientSimple.createUser:createUser·p0.99    sample          8.275           ms/op
ClientSimple.createUser:createUser·p0.999   sample         19.431           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         20.119           ms/op
ClientSimple.createUser:createUser·p1.00    sample         20.251           ms/op
ClientSimple.existUser                      sample  18445   1.743 ± 0.015   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.606           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.647           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.089           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.318           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.470           ms/op
ClientSimple.existUser:existUser·p0.999     sample         12.503           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         13.517           ms/op
ClientSimple.existUser:existUser·p1.00      sample         13.517           ms/op
ClientSimple.getUser                        sample  15349   2.087 ± 0.019   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.748           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.972           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.564           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.847           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.620           ms/op
ClientSimple.getUser:getUser·p0.999         sample         11.889           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         12.705           ms/op
ClientSimple.getUser:getUser·p1.00          sample         12.714           ms/op
ClientSimple.listUser                       sample   8610   3.712 ± 0.066   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.788           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.690           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.571           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.899           ms/op
ClientSimple.listUser:listUser·p0.99        sample          8.895           ms/op
ClientSimple.listUser:listUser·p0.999       sample         28.390           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         29.032           ms/op
ClientSimple.listUser:listUser·p1.00        sample         29.032           ms/op

Benchmark result is saved to 1713507136743.json
