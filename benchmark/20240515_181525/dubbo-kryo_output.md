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
# Warmup Iteration   1: 1.666 ops/ms
Iteration   1: 7.439 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.439 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.574 ops/ms
Iteration   1: 12.297 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.297 ops/ms


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
# Warmup Iteration   1: 6.395 ops/ms
Iteration   1: 12.455 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.455 ops/ms


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
# Warmup Iteration   1: 4.058 ops/ms
Iteration   1: 7.944 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  7.944 ops/ms


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
# Warmup Iteration   1: 4.006 ±(99.9%) 0.076 ms/op
Iteration   1: 2.300 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.300 ms/op


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
# Warmup Iteration   1: 3.683 ±(99.9%) 0.083 ms/op
Iteration   1: 1.599 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.599 ms/op


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
# Warmup Iteration   1: 3.416 ±(99.9%) 0.059 ms/op
Iteration   1: 2.009 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.009 ms/op


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
# Warmup Iteration   1: 4.616 ±(99.9%) 0.111 ms/op
Iteration   1: 3.621 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.621 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 4.095 ±(99.9%) 0.144 ms/op
Iteration   1: 2.192 ±(99.9%) 0.031 ms/op
                 createUser·p0.00:   0.753 ms/op
                 createUser·p0.50:   2.021 ms/op
                 createUser·p0.90:   2.839 ms/op
                 createUser·p0.95:   3.109 ms/op
                 createUser·p0.99:   8.708 ms/op
                 createUser·p0.999:  15.335 ms/op
                 createUser·p0.9999: 15.639 ms/op
                 createUser·p1.00:   15.647 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14525
  mean =      2.192 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 134 
    [ 1.250,  2.500) = 11791 
    [ 2.500,  3.750) = 2367 
    [ 3.750,  5.000) = 66 
    [ 5.000,  6.250) = 14 
    [ 6.250,  7.500) = 4 
    [ 7.500,  8.750) = 7 
    [ 8.750, 10.000) = 48 
    [10.000, 11.250) = 23 
    [11.250, 12.500) = 7 
    [12.500, 13.750) = 18 
    [13.750, 15.000) = 31 
    [15.000, 16.250) = 15 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.753 ms/op
     p(50.0000) =      2.021 ms/op
     p(90.0000) =      2.839 ms/op
     p(95.0000) =      3.109 ms/op
     p(99.0000) =      8.708 ms/op
     p(99.9000) =     15.335 ms/op
     p(99.9900) =     15.639 ms/op
     p(99.9990) =     15.647 ms/op
     p(99.9999) =     15.647 ms/op
    p(100.0000) =     15.647 ms/op


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
# Warmup Iteration   1: 2.941 ±(99.9%) 0.069 ms/op
Iteration   1: 1.897 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   0.558 ms/op
                 existUser·p0.50:   1.761 ms/op
                 existUser·p0.90:   2.437 ms/op
                 existUser·p0.95:   2.634 ms/op
                 existUser·p0.99:   3.021 ms/op
                 existUser·p0.999:  12.337 ms/op
                 existUser·p0.9999: 13.149 ms/op
                 existUser·p1.00:   13.287 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17037
  mean =      1.897 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 292 
    [ 1.250,  2.500) = 15393 
    [ 2.500,  3.750) = 1261 
    [ 3.750,  5.000) = 27 
    [ 5.000,  6.250) = 14 
    [ 6.250,  7.500) = 18 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 17 
    [12.500, 13.750) = 14 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.558 ms/op
     p(50.0000) =      1.761 ms/op
     p(90.0000) =      2.437 ms/op
     p(95.0000) =      2.634 ms/op
     p(99.0000) =      3.021 ms/op
     p(99.9000) =     12.337 ms/op
     p(99.9900) =     13.149 ms/op
     p(99.9990) =     13.287 ms/op
     p(99.9999) =     13.287 ms/op
    p(100.0000) =     13.287 ms/op


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
# Warmup Iteration   1: 3.572 ±(99.9%) 0.109 ms/op
Iteration   1: 2.183 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   0.513 ms/op
                 getUser·p0.50:   2.073 ms/op
                 getUser·p0.90:   2.781 ms/op
                 getUser·p0.95:   3.047 ms/op
                 getUser·p0.99:   3.686 ms/op
                 getUser·p0.999:  10.764 ms/op
                 getUser·p0.9999: 11.084 ms/op
                 getUser·p1.00:   11.092 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14732
  mean =      2.183 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 78 
    [ 1.250,  2.500) = 11963 
    [ 2.500,  3.750) = 2556 
    [ 3.750,  5.000) = 98 
    [ 5.000,  6.250) = 5 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 32 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.513 ms/op
     p(50.0000) =      2.073 ms/op
     p(90.0000) =      2.781 ms/op
     p(95.0000) =      3.047 ms/op
     p(99.0000) =      3.686 ms/op
     p(99.9000) =     10.764 ms/op
     p(99.9900) =     11.084 ms/op
     p(99.9990) =     11.092 ms/op
     p(99.9999) =     11.092 ms/op
    p(100.0000) =     11.092 ms/op


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
# Warmup Iteration   1: 4.317 ±(99.9%) 0.128 ms/op
Iteration   1: 3.221 ±(99.9%) 0.032 ms/op
                 listUser·p0.00:   1.135 ms/op
                 listUser·p0.50:   3.170 ms/op
                 listUser·p0.90:   4.007 ms/op
                 listUser·p0.95:   4.227 ms/op
                 listUser·p0.99:   5.696 ms/op
                 listUser·p0.999:  14.746 ms/op
                 listUser·p0.9999: 14.893 ms/op
                 listUser·p1.00:   14.893 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9936
  mean =      3.221 ±(99.9%) 0.032 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 9 
    [ 1.250,  2.500) = 1297 
    [ 2.500,  3.750) = 6908 
    [ 3.750,  5.000) = 1547 
    [ 5.000,  6.250) = 100 
    [ 6.250,  7.500) = 32 
    [ 7.500,  8.750) = 11 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.135 ms/op
     p(50.0000) =      3.170 ms/op
     p(90.0000) =      4.007 ms/op
     p(95.0000) =      4.227 ms/op
     p(99.0000) =      5.696 ms/op
     p(99.9000) =     14.746 ms/op
     p(99.9900) =     14.893 ms/op
     p(99.9990) =     14.893 ms/op
     p(99.9999) =     14.893 ms/op
    p(100.0000) =     14.893 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.439          ops/ms
ClientSimple.existUser                       thrpt         12.297          ops/ms
ClientSimple.getUser                         thrpt         12.455          ops/ms
ClientSimple.listUser                        thrpt          7.944          ops/ms
ClientSimple.createUser                       avgt          2.300           ms/op
ClientSimple.existUser                        avgt          1.599           ms/op
ClientSimple.getUser                          avgt          2.009           ms/op
ClientSimple.listUser                         avgt          3.621           ms/op
ClientSimple.createUser                     sample  14525   2.192 ± 0.031   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.753           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.021           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.839           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.109           ms/op
ClientSimple.createUser:createUser·p0.99    sample          8.708           ms/op
ClientSimple.createUser:createUser·p0.999   sample         15.335           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         15.639           ms/op
ClientSimple.createUser:createUser·p1.00    sample         15.647           ms/op
ClientSimple.existUser                      sample  17037   1.897 ± 0.016   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.558           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.761           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.437           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.634           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.021           ms/op
ClientSimple.existUser:existUser·p0.999     sample         12.337           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         13.149           ms/op
ClientSimple.existUser:existUser·p1.00      sample         13.287           ms/op
ClientSimple.getUser                        sample  14732   2.183 ± 0.016   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.513           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.073           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.781           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.047           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.686           ms/op
ClientSimple.getUser:getUser·p0.999         sample         10.764           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         11.084           ms/op
ClientSimple.getUser:getUser·p1.00          sample         11.092           ms/op
ClientSimple.listUser                       sample   9936   3.221 ± 0.032   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.135           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.170           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.007           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.227           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.696           ms/op
ClientSimple.listUser:listUser·p0.999       sample         14.746           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         14.893           ms/op
ClientSimple.listUser:listUser·p1.00        sample         14.893           ms/op

Benchmark result is saved to 1715796669099.json
