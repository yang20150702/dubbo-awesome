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
# Warmup Iteration   1: 1.513 ops/ms
Iteration   1: 5.860 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  5.860 ops/ms


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
# Warmup Iteration   1: 5.894 ops/ms
Iteration   1: 11.922 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.922 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:11
# Fork: 1 of 1
# Warmup Iteration   1: 4.686 ops/ms
Iteration   1: 11.899 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.899 ops/ms


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
# Warmup Iteration   1: 5.601 ops/ms
Iteration   1: 8.269 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.269 ops/ms


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
# Warmup Iteration   1: 4.736 ±(99.9%) 0.093 ms/op
Iteration   1: 2.448 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.448 ms/op


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
# Warmup Iteration   1: 3.726 ±(99.9%) 0.089 ms/op
Iteration   1: 1.892 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.892 ms/op


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
# Warmup Iteration   1: 3.269 ±(99.9%) 0.068 ms/op
Iteration   1: 2.263 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.263 ms/op


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
# Warmup Iteration   1: 6.409 ±(99.9%) 0.133 ms/op
Iteration   1: 3.714 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.714 ms/op


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
# Warmup Iteration   1: 4.014 ±(99.9%) 0.122 ms/op
Iteration   1: 2.241 ±(99.9%) 0.033 ms/op
                 createUser·p0.00:   0.548 ms/op
                 createUser·p0.50:   2.114 ms/op
                 createUser·p0.90:   2.707 ms/op
                 createUser·p0.95:   2.961 ms/op
                 createUser·p0.99:   6.640 ms/op
                 createUser·p0.999:  17.826 ms/op
                 createUser·p0.9999: 18.781 ms/op
                 createUser·p1.00:   19.005 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14271
  mean =      2.241 ±(99.9%) 0.033 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 293 
    [ 1.250,  2.500) = 11155 
    [ 2.500,  3.750) = 2569 
    [ 3.750,  5.000) = 72 
    [ 5.000,  6.250) = 18 
    [ 6.250,  7.500) = 59 
    [ 7.500,  8.750) = 9 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 31 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 21 
    [15.000, 16.250) = 5 
    [16.250, 17.500) = 11 
    [17.500, 18.750) = 26 

  Percentiles, ms/op:
      p(0.0000) =      0.548 ms/op
     p(50.0000) =      2.114 ms/op
     p(90.0000) =      2.707 ms/op
     p(95.0000) =      2.961 ms/op
     p(99.0000) =      6.640 ms/op
     p(99.9000) =     17.826 ms/op
     p(99.9900) =     18.781 ms/op
     p(99.9990) =     19.005 ms/op
     p(99.9999) =     19.005 ms/op
    p(100.0000) =     19.005 ms/op


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
# Warmup Iteration   1: 3.028 ±(99.9%) 0.073 ms/op
Iteration   1: 2.258 ±(99.9%) 0.024 ms/op
                 existUser·p0.00:   0.443 ms/op
                 existUser·p0.50:   2.167 ms/op
                 existUser·p0.90:   2.789 ms/op
                 existUser·p0.95:   2.986 ms/op
                 existUser·p0.99:   5.710 ms/op
                 existUser·p0.999:  12.334 ms/op
                 existUser·p0.9999: 12.680 ms/op
                 existUser·p1.00:   12.714 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 14202
  mean =      2.258 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 307 
    [ 1.250,  2.500) = 9871 
    [ 2.500,  3.750) = 3766 
    [ 3.750,  5.000) = 97 
    [ 5.000,  6.250) = 33 
    [ 6.250,  7.500) = 13 
    [ 7.500,  8.750) = 52 
    [ 8.750, 10.000) = 31 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 29 
    [12.500, 13.750) = 3 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.443 ms/op
     p(50.0000) =      2.167 ms/op
     p(90.0000) =      2.789 ms/op
     p(95.0000) =      2.986 ms/op
     p(99.0000) =      5.710 ms/op
     p(99.9000) =     12.334 ms/op
     p(99.9900) =     12.680 ms/op
     p(99.9990) =     12.714 ms/op
     p(99.9999) =     12.714 ms/op
    p(100.0000) =     12.714 ms/op


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
# Warmup Iteration   1: 3.631 ±(99.9%) 0.118 ms/op
Iteration   1: 2.380 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   0.477 ms/op
                 getUser·p0.50:   2.318 ms/op
                 getUser·p0.90:   2.875 ms/op
                 getUser·p0.95:   3.178 ms/op
                 getUser·p0.99:   5.130 ms/op
                 getUser·p0.999:  12.265 ms/op
                 getUser·p0.9999: 12.632 ms/op
                 getUser·p1.00:   12.648 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 13428
  mean =      2.380 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 131 
    [ 1.250,  2.500) = 8791 
    [ 2.500,  3.750) = 4166 
    [ 3.750,  5.000) = 201 
    [ 5.000,  6.250) = 65 
    [ 6.250,  7.500) = 41 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 29 
    [12.500, 13.750) = 3 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.477 ms/op
     p(50.0000) =      2.318 ms/op
     p(90.0000) =      2.875 ms/op
     p(95.0000) =      3.178 ms/op
     p(99.0000) =      5.130 ms/op
     p(99.9000) =     12.265 ms/op
     p(99.9900) =     12.632 ms/op
     p(99.9990) =     12.648 ms/op
     p(99.9999) =     12.648 ms/op
    p(100.0000) =     12.648 ms/op


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
# Warmup Iteration   1: 4.360 ±(99.9%) 0.133 ms/op
Iteration   1: 3.407 ±(99.9%) 0.047 ms/op
                 listUser·p0.00:   1.225 ms/op
                 listUser·p0.50:   3.195 ms/op
                 listUser·p0.90:   4.661 ms/op
                 listUser·p0.95:   5.210 ms/op
                 listUser·p0.99:   7.105 ms/op
                 listUser·p0.999:  19.943 ms/op
                 listUser·p0.9999: 20.709 ms/op
                 listUser·p1.00:   20.709 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9386
  mean =      3.407 ±(99.9%) 0.047 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2235 
    [ 2.500,  5.000) = 6520 
    [ 5.000,  7.500) = 547 
    [ 7.500, 10.000) = 49 
    [10.000, 12.500) = 4 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.225 ms/op
     p(50.0000) =      3.195 ms/op
     p(90.0000) =      4.661 ms/op
     p(95.0000) =      5.210 ms/op
     p(99.0000) =      7.105 ms/op
     p(99.9000) =     19.943 ms/op
     p(99.9900) =     20.709 ms/op
     p(99.9990) =     20.709 ms/op
     p(99.9999) =     20.709 ms/op
    p(100.0000) =     20.709 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          5.860          ops/ms
ClientSimple.existUser                       thrpt         11.922          ops/ms
ClientSimple.getUser                         thrpt         11.899          ops/ms
ClientSimple.listUser                        thrpt          8.269          ops/ms
ClientSimple.createUser                       avgt          2.448           ms/op
ClientSimple.existUser                        avgt          1.892           ms/op
ClientSimple.getUser                          avgt          2.263           ms/op
ClientSimple.listUser                         avgt          3.714           ms/op
ClientSimple.createUser                     sample  14271   2.241 ± 0.033   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.548           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.114           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.707           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.961           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.640           ms/op
ClientSimple.createUser:createUser·p0.999   sample         17.826           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         18.781           ms/op
ClientSimple.createUser:createUser·p1.00    sample         19.005           ms/op
ClientSimple.existUser                      sample  14202   2.258 ± 0.024   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.443           ms/op
ClientSimple.existUser:existUser·p0.50      sample          2.167           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.789           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.986           ms/op
ClientSimple.existUser:existUser·p0.99      sample          5.710           ms/op
ClientSimple.existUser:existUser·p0.999     sample         12.334           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         12.680           ms/op
ClientSimple.existUser:existUser·p1.00      sample         12.714           ms/op
ClientSimple.getUser                        sample  13428   2.380 ± 0.021   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.477           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.318           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.875           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.178           ms/op
ClientSimple.getUser:getUser·p0.99          sample          5.130           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.265           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         12.632           ms/op
ClientSimple.getUser:getUser·p1.00          sample         12.648           ms/op
ClientSimple.listUser                       sample   9386   3.407 ± 0.047   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.225           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.195           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.661           ms/op
ClientSimple.listUser:listUser·p0.95        sample          5.210           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.105           ms/op
ClientSimple.listUser:listUser·p0.999       sample         19.943           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         20.709           ms/op
ClientSimple.listUser:listUser·p1.00        sample         20.709           ms/op

Benchmark result is saved to 1715926352109.json
