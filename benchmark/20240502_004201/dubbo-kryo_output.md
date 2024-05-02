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
# Warmup Iteration   1: 1.659 ops/ms
Iteration   1: 7.261 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.261 ops/ms


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
# Warmup Iteration   1: 6.105 ops/ms
Iteration   1: 12.488 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.488 ops/ms


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
# Warmup Iteration   1: 4.707 ops/ms
Iteration   1: 14.030 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  14.030 ops/ms


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
# Warmup Iteration   1: 5.250 ops/ms
Iteration   1: 9.438 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.438 ops/ms


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
# Warmup Iteration   1: 3.798 ±(99.9%) 0.078 ms/op
Iteration   1: 2.168 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.168 ms/op


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
# Warmup Iteration   1: 3.204 ±(99.9%) 0.047 ms/op
Iteration   1: 1.765 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.765 ms/op


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
# Warmup Iteration   1: 3.629 ±(99.9%) 0.056 ms/op
Iteration   1: 2.157 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.157 ms/op


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
# Warmup Iteration   1: 4.486 ±(99.9%) 0.098 ms/op
Iteration   1: 3.236 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.236 ms/op


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
# Warmup Iteration   1: 3.585 ±(99.9%) 0.086 ms/op
Iteration   1: 2.122 ±(99.9%) 0.029 ms/op
                 createUser·p0.00:   0.485 ms/op
                 createUser·p0.50:   1.956 ms/op
                 createUser·p0.90:   2.449 ms/op
                 createUser·p0.95:   3.006 ms/op
                 createUser·p0.99:   7.936 ms/op
                 createUser·p0.999:  13.861 ms/op
                 createUser·p0.9999: 14.376 ms/op
                 createUser·p1.00:   14.451 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15062
  mean =      2.122 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 161 
    [ 1.250,  2.500) = 13615 
    [ 2.500,  3.750) = 733 
    [ 3.750,  5.000) = 206 
    [ 5.000,  6.250) = 154 
    [ 6.250,  7.500) = 32 
    [ 7.500,  8.750) = 33 
    [ 8.750, 10.000) = 27 
    [10.000, 11.250) = 30 
    [11.250, 12.500) = 39 
    [12.500, 13.750) = 5 
    [13.750, 15.000) = 27 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.485 ms/op
     p(50.0000) =      1.956 ms/op
     p(90.0000) =      2.449 ms/op
     p(95.0000) =      3.006 ms/op
     p(99.0000) =      7.936 ms/op
     p(99.9000) =     13.861 ms/op
     p(99.9900) =     14.376 ms/op
     p(99.9990) =     14.451 ms/op
     p(99.9999) =     14.451 ms/op
    p(100.0000) =     14.451 ms/op


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
# Warmup Iteration   1: 3.088 ±(99.9%) 0.072 ms/op
Iteration   1: 2.320 ±(99.9%) 0.036 ms/op
                 existUser·p0.00:   0.415 ms/op
                 existUser·p0.50:   2.277 ms/op
                 existUser·p0.90:   2.793 ms/op
                 existUser·p0.95:   2.986 ms/op
                 existUser·p0.99:   5.445 ms/op
                 existUser·p0.999:  24.156 ms/op
                 existUser·p0.9999: 24.723 ms/op
                 existUser·p1.00:   24.773 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 13817
  mean =      2.320 ±(99.9%) 0.036 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9636 
    [ 2.500,  5.000) = 4009 
    [ 5.000,  7.500) = 108 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.415 ms/op
     p(50.0000) =      2.277 ms/op
     p(90.0000) =      2.793 ms/op
     p(95.0000) =      2.986 ms/op
     p(99.0000) =      5.445 ms/op
     p(99.9000) =     24.156 ms/op
     p(99.9900) =     24.723 ms/op
     p(99.9990) =     24.773 ms/op
     p(99.9999) =     24.773 ms/op
    p(100.0000) =     24.773 ms/op


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
# Warmup Iteration   1: 3.254 ±(99.9%) 0.081 ms/op
Iteration   1: 2.100 ±(99.9%) 0.028 ms/op
                 getUser·p0.00:   0.599 ms/op
                 getUser·p0.50:   2.010 ms/op
                 getUser·p0.90:   2.556 ms/op
                 getUser·p0.95:   2.740 ms/op
                 getUser·p0.99:   3.367 ms/op
                 getUser·p0.999:  23.017 ms/op
                 getUser·p0.9999: 23.408 ms/op
                 getUser·p1.00:   23.495 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15294
  mean =      2.100 ±(99.9%) 0.028 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13419 
    [ 2.500,  5.000) = 1809 
    [ 5.000,  7.500) = 34 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.599 ms/op
     p(50.0000) =      2.010 ms/op
     p(90.0000) =      2.556 ms/op
     p(95.0000) =      2.740 ms/op
     p(99.0000) =      3.367 ms/op
     p(99.9000) =     23.017 ms/op
     p(99.9900) =     23.408 ms/op
     p(99.9990) =     23.495 ms/op
     p(99.9999) =     23.495 ms/op
    p(100.0000) =     23.495 ms/op


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
# Warmup Iteration   1: 5.395 ±(99.9%) 0.163 ms/op
Iteration   1: 3.554 ±(99.9%) 0.057 ms/op
                 listUser·p0.00:   0.908 ms/op
                 listUser·p0.50:   3.400 ms/op
                 listUser·p0.90:   4.412 ms/op
                 listUser·p0.95:   5.226 ms/op
                 listUser·p0.99:   9.221 ms/op
                 listUser·p0.999:  22.839 ms/op
                 listUser·p0.9999: 23.069 ms/op
                 listUser·p1.00:   23.069 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9003
  mean =      3.554 ±(99.9%) 0.057 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 883 
    [ 2.500,  5.000) = 7605 
    [ 5.000,  7.500) = 382 
    [ 7.500, 10.000) = 56 
    [10.000, 12.500) = 13 
    [12.500, 15.000) = 19 
    [15.000, 17.500) = 12 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.908 ms/op
     p(50.0000) =      3.400 ms/op
     p(90.0000) =      4.412 ms/op
     p(95.0000) =      5.226 ms/op
     p(99.0000) =      9.221 ms/op
     p(99.9000) =     22.839 ms/op
     p(99.9900) =     23.069 ms/op
     p(99.9990) =     23.069 ms/op
     p(99.9999) =     23.069 ms/op
    p(100.0000) =     23.069 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.261          ops/ms
ClientSimple.existUser                       thrpt         12.488          ops/ms
ClientSimple.getUser                         thrpt         14.030          ops/ms
ClientSimple.listUser                        thrpt          9.438          ops/ms
ClientSimple.createUser                       avgt          2.168           ms/op
ClientSimple.existUser                        avgt          1.765           ms/op
ClientSimple.getUser                          avgt          2.157           ms/op
ClientSimple.listUser                         avgt          3.236           ms/op
ClientSimple.createUser                     sample  15062   2.122 ± 0.029   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.485           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.956           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.449           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.006           ms/op
ClientSimple.createUser:createUser·p0.99    sample          7.936           ms/op
ClientSimple.createUser:createUser·p0.999   sample         13.861           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         14.376           ms/op
ClientSimple.createUser:createUser·p1.00    sample         14.451           ms/op
ClientSimple.existUser                      sample  13817   2.320 ± 0.036   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.415           ms/op
ClientSimple.existUser:existUser·p0.50      sample          2.277           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.793           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.986           ms/op
ClientSimple.existUser:existUser·p0.99      sample          5.445           ms/op
ClientSimple.existUser:existUser·p0.999     sample         24.156           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         24.723           ms/op
ClientSimple.existUser:existUser·p1.00      sample         24.773           ms/op
ClientSimple.getUser                        sample  15294   2.100 ± 0.028   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.599           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.010           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.556           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.740           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.367           ms/op
ClientSimple.getUser:getUser·p0.999         sample         23.017           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         23.408           ms/op
ClientSimple.getUser:getUser·p1.00          sample         23.495           ms/op
ClientSimple.listUser                       sample   9003   3.554 ± 0.057   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.908           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.400           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.412           ms/op
ClientSimple.listUser:listUser·p0.95        sample          5.226           ms/op
ClientSimple.listUser:listUser·p0.99        sample          9.221           ms/op
ClientSimple.listUser:listUser·p0.999       sample         22.839           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         23.069           ms/op
ClientSimple.listUser:listUser·p1.00        sample         23.069           ms/op

Benchmark result is saved to 1714610264033.json
