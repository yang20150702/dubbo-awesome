# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 1.807 ops/ms
Iteration   1: 7.285 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.285 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 5.934 ops/ms
Iteration   1: 12.492 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.492 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 6.097 ops/ms
Iteration   1: 13.185 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.185 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 4.706 ops/ms
Iteration   1: 8.804 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.804 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 4.190 ±(99.9%) 0.075 ms/op
Iteration   1: 2.013 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.013 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.941 ±(99.9%) 0.066 ms/op
Iteration   1: 2.060 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.060 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 3.217 ±(99.9%) 0.053 ms/op
Iteration   1: 1.744 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.744 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 5.091 ±(99.9%) 0.098 ms/op
Iteration   1: 3.523 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.523 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.404 ±(99.9%) 0.095 ms/op
Iteration   1: 2.237 ±(99.9%) 0.026 ms/op
                 createUser·p0.00:   0.529 ms/op
                 createUser·p0.50:   2.114 ms/op
                 createUser·p0.90:   2.691 ms/op
                 createUser·p0.95:   3.002 ms/op
                 createUser·p0.99:   5.629 ms/op
                 createUser·p0.999:  17.367 ms/op
                 createUser·p0.9999: 18.813 ms/op
                 createUser·p1.00:   19.235 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14286
  mean =      2.237 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 54 
    [ 1.250,  2.500) = 11778 
    [ 2.500,  3.750) = 2130 
    [ 3.750,  5.000) = 134 
    [ 5.000,  6.250) = 104 
    [ 6.250,  7.500) = 36 
    [ 7.500,  8.750) = 3 
    [ 8.750, 10.000) = 12 
    [10.000, 11.250) = 3 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 28 
    [17.500, 18.750) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.529 ms/op
     p(50.0000) =      2.114 ms/op
     p(90.0000) =      2.691 ms/op
     p(95.0000) =      3.002 ms/op
     p(99.0000) =      5.629 ms/op
     p(99.9000) =     17.367 ms/op
     p(99.9900) =     18.813 ms/op
     p(99.9990) =     19.235 ms/op
     p(99.9999) =     19.235 ms/op
    p(100.0000) =     19.235 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 2.842 ±(99.9%) 0.082 ms/op
Iteration   1: 1.955 ±(99.9%) 0.023 ms/op
                 existUser·p0.00:   0.781 ms/op
                 existUser·p0.50:   1.858 ms/op
                 existUser·p0.90:   2.544 ms/op
                 existUser·p0.95:   2.753 ms/op
                 existUser·p0.99:   3.735 ms/op
                 existUser·p0.999:  18.514 ms/op
                 existUser·p0.9999: 19.107 ms/op
                 existUser·p1.00:   19.857 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16359
  mean =      1.955 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 509 
    [ 1.250,  2.500) = 13968 
    [ 2.500,  3.750) = 1723 
    [ 3.750,  5.000) = 109 
    [ 5.000,  6.250) = 6 
    [ 6.250,  7.500) = 11 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 31 

  Percentiles, ms/op:
      p(0.0000) =      0.781 ms/op
     p(50.0000) =      1.858 ms/op
     p(90.0000) =      2.544 ms/op
     p(95.0000) =      2.753 ms/op
     p(99.0000) =      3.735 ms/op
     p(99.9000) =     18.514 ms/op
     p(99.9900) =     19.107 ms/op
     p(99.9990) =     19.857 ms/op
     p(99.9999) =     19.857 ms/op
    p(100.0000) =     19.857 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.559 ±(99.9%) 0.103 ms/op
Iteration   1: 2.011 ±(99.9%) 0.031 ms/op
                 getUser·p0.00:   0.604 ms/op
                 getUser·p0.50:   1.827 ms/op
                 getUser·p0.90:   2.535 ms/op
                 getUser·p0.95:   2.892 ms/op
                 getUser·p0.99:   3.755 ms/op
                 getUser·p0.999:  23.003 ms/op
                 getUser·p0.9999: 23.265 ms/op
                 getUser·p1.00:   23.265 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15915
  mean =      2.011 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14241 
    [ 2.500,  5.000) = 1597 
    [ 5.000,  7.500) = 13 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 3 
    [15.000, 17.500) = 29 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.604 ms/op
     p(50.0000) =      1.827 ms/op
     p(90.0000) =      2.535 ms/op
     p(95.0000) =      2.892 ms/op
     p(99.0000) =      3.755 ms/op
     p(99.9000) =     23.003 ms/op
     p(99.9900) =     23.265 ms/op
     p(99.9990) =     23.265 ms/op
     p(99.9999) =     23.265 ms/op
    p(100.0000) =     23.265 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.895 ±(99.9%) 0.188 ms/op
Iteration   1: 3.647 ±(99.9%) 0.034 ms/op
                 listUser·p0.00:   1.255 ms/op
                 listUser·p0.50:   3.621 ms/op
                 listUser·p0.90:   4.227 ms/op
                 listUser·p0.95:   4.522 ms/op
                 listUser·p0.99:   6.955 ms/op
                 listUser·p0.999:  15.617 ms/op
                 listUser·p0.9999: 16.482 ms/op
                 listUser·p1.00:   16.482 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8802
  mean =      3.647 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 308 
    [ 2.500,  3.750) = 5142 
    [ 3.750,  5.000) = 3108 
    [ 5.000,  6.250) = 92 
    [ 6.250,  7.500) = 119 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 29 
    [16.250, 17.500) = 2 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.255 ms/op
     p(50.0000) =      3.621 ms/op
     p(90.0000) =      4.227 ms/op
     p(95.0000) =      4.522 ms/op
     p(99.0000) =      6.955 ms/op
     p(99.9000) =     15.617 ms/op
     p(99.9900) =     16.482 ms/op
     p(99.9990) =     16.482 ms/op
     p(99.9999) =     16.482 ms/op
    p(100.0000) =     16.482 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.285          ops/ms
ClientSimple.existUser                       thrpt         12.492          ops/ms
ClientSimple.getUser                         thrpt         13.185          ops/ms
ClientSimple.listUser                        thrpt          8.804          ops/ms
ClientSimple.createUser                       avgt          2.013           ms/op
ClientSimple.existUser                        avgt          2.060           ms/op
ClientSimple.getUser                          avgt          1.744           ms/op
ClientSimple.listUser                         avgt          3.523           ms/op
ClientSimple.createUser                     sample  14286   2.237 ± 0.026   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.529           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.114           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.691           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.002           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.629           ms/op
ClientSimple.createUser:createUser·p0.999   sample         17.367           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         18.813           ms/op
ClientSimple.createUser:createUser·p1.00    sample         19.235           ms/op
ClientSimple.existUser                      sample  16359   1.955 ± 0.023   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.781           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.858           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.544           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.753           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.735           ms/op
ClientSimple.existUser:existUser·p0.999     sample         18.514           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         19.107           ms/op
ClientSimple.existUser:existUser·p1.00      sample         19.857           ms/op
ClientSimple.getUser                        sample  15915   2.011 ± 0.031   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.604           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.827           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.535           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.892           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.755           ms/op
ClientSimple.getUser:getUser·p0.999         sample         23.003           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         23.265           ms/op
ClientSimple.getUser:getUser·p1.00          sample         23.265           ms/op
ClientSimple.listUser                       sample   8802   3.647 ± 0.034   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.255           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.621           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.227           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.522           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.955           ms/op
ClientSimple.listUser:listUser·p0.999       sample         15.617           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         16.482           ms/op
ClientSimple.listUser:listUser·p1.00        sample         16.482           ms/op

Benchmark result is saved to 1716228704181.json
