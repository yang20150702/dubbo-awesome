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
# Warmup Iteration   1: 1.637 ops/ms
Iteration   1: 6.991 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.991 ops/ms


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
# Warmup Iteration   1: 6.303 ops/ms
Iteration   1: 11.088 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.088 ops/ms


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
# Warmup Iteration   1: 5.556 ops/ms
Iteration   1: 12.654 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.654 ops/ms


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
# Warmup Iteration   1: 5.187 ops/ms
Iteration   1: 8.823 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.823 ops/ms


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
# Warmup Iteration   1: 3.816 ±(99.9%) 0.069 ms/op
Iteration   1: 2.202 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.202 ms/op


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
# Warmup Iteration   1: 3.091 ±(99.9%) 0.056 ms/op
Iteration   1: 1.669 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.669 ms/op


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
# Warmup Iteration   1: 3.305 ±(99.9%) 0.056 ms/op
Iteration   1: 2.041 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.041 ms/op


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
# Warmup Iteration   1: 4.165 ±(99.9%) 0.087 ms/op
Iteration   1: 3.783 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.783 ms/op


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
# Warmup Iteration   1: 3.236 ±(99.9%) 0.077 ms/op
Iteration   1: 2.040 ±(99.9%) 0.029 ms/op
                 createUser·p0.00:   0.522 ms/op
                 createUser·p0.50:   1.839 ms/op
                 createUser·p0.90:   2.441 ms/op
                 createUser·p0.95:   2.744 ms/op
                 createUser·p0.99:   6.502 ms/op
                 createUser·p0.999:  18.590 ms/op
                 createUser·p0.9999: 22.068 ms/op
                 createUser·p1.00:   22.217 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15671
  mean =      2.040 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14256 
    [ 2.500,  5.000) = 1195 
    [ 5.000,  7.500) = 108 
    [ 7.500, 10.000) = 48 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.522 ms/op
     p(50.0000) =      1.839 ms/op
     p(90.0000) =      2.441 ms/op
     p(95.0000) =      2.744 ms/op
     p(99.0000) =      6.502 ms/op
     p(99.9000) =     18.590 ms/op
     p(99.9900) =     22.068 ms/op
     p(99.9990) =     22.217 ms/op
     p(99.9999) =     22.217 ms/op
    p(100.0000) =     22.217 ms/op


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
# Warmup Iteration   1: 3.240 ±(99.9%) 0.158 ms/op
Iteration   1: 2.035 ±(99.9%) 0.031 ms/op
                 existUser·p0.00:   0.640 ms/op
                 existUser·p0.50:   1.909 ms/op
                 existUser·p0.90:   2.404 ms/op
                 existUser·p0.95:   2.705 ms/op
                 existUser·p0.99:   5.923 ms/op
                 existUser·p0.999:  22.741 ms/op
                 existUser·p0.9999: 23.158 ms/op
                 existUser·p1.00:   23.233 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15711
  mean =      2.035 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14500 
    [ 2.500,  5.000) = 1039 
    [ 5.000,  7.500) = 43 
    [ 7.500, 10.000) = 92 
    [10.000, 12.500) = 5 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.640 ms/op
     p(50.0000) =      1.909 ms/op
     p(90.0000) =      2.404 ms/op
     p(95.0000) =      2.705 ms/op
     p(99.0000) =      5.923 ms/op
     p(99.9000) =     22.741 ms/op
     p(99.9900) =     23.158 ms/op
     p(99.9990) =     23.233 ms/op
     p(99.9999) =     23.233 ms/op
    p(100.0000) =     23.233 ms/op


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
# Warmup Iteration   1: 3.498 ±(99.9%) 0.087 ms/op
Iteration   1: 1.881 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   0.898 ms/op
                 getUser·p0.50:   1.810 ms/op
                 getUser·p0.90:   2.122 ms/op
                 getUser·p0.95:   2.294 ms/op
                 getUser·p0.99:   2.720 ms/op
                 getUser·p0.999:  16.695 ms/op
                 getUser·p0.9999: 16.885 ms/op
                 getUser·p1.00:   16.908 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16999
  mean =      1.881 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 59 
    [ 1.250,  2.500) = 16521 
    [ 2.500,  3.750) = 379 
    [ 3.750,  5.000) = 5 
    [ 5.000,  6.250) = 3 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 32 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.898 ms/op
     p(50.0000) =      1.810 ms/op
     p(90.0000) =      2.122 ms/op
     p(95.0000) =      2.294 ms/op
     p(99.0000) =      2.720 ms/op
     p(99.9000) =     16.695 ms/op
     p(99.9900) =     16.885 ms/op
     p(99.9990) =     16.908 ms/op
     p(99.9999) =     16.908 ms/op
    p(100.0000) =     16.908 ms/op


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
# Warmup Iteration   1: 4.906 ±(99.9%) 0.140 ms/op
Iteration   1: 3.174 ±(99.9%) 0.034 ms/op
                 listUser·p0.00:   1.118 ms/op
                 listUser·p0.50:   2.961 ms/op
                 listUser·p0.90:   3.990 ms/op
                 listUser·p0.95:   4.327 ms/op
                 listUser·p0.99:   5.669 ms/op
                 listUser·p0.999:  16.738 ms/op
                 listUser·p0.9999: 17.856 ms/op
                 listUser·p1.00:   17.859 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10055
  mean =      3.174 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3 
    [ 1.250,  2.500) = 1719 
    [ 2.500,  3.750) = 6362 
    [ 3.750,  5.000) = 1826 
    [ 5.000,  6.250) = 75 
    [ 6.250,  7.500) = 34 
    [ 7.500,  8.750) = 4 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 14 
    [16.250, 17.500) = 17 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.118 ms/op
     p(50.0000) =      2.961 ms/op
     p(90.0000) =      3.990 ms/op
     p(95.0000) =      4.327 ms/op
     p(99.0000) =      5.669 ms/op
     p(99.9000) =     16.738 ms/op
     p(99.9900) =     17.856 ms/op
     p(99.9990) =     17.859 ms/op
     p(99.9999) =     17.859 ms/op
    p(100.0000) =     17.859 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.991          ops/ms
ClientSimple.existUser                       thrpt         11.088          ops/ms
ClientSimple.getUser                         thrpt         12.654          ops/ms
ClientSimple.listUser                        thrpt          8.823          ops/ms
ClientSimple.createUser                       avgt          2.202           ms/op
ClientSimple.existUser                        avgt          1.669           ms/op
ClientSimple.getUser                          avgt          2.041           ms/op
ClientSimple.listUser                         avgt          3.783           ms/op
ClientSimple.createUser                     sample  15671   2.040 ± 0.029   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.522           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.839           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.441           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.744           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.502           ms/op
ClientSimple.createUser:createUser·p0.999   sample         18.590           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         22.068           ms/op
ClientSimple.createUser:createUser·p1.00    sample         22.217           ms/op
ClientSimple.existUser                      sample  15711   2.035 ± 0.031   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.640           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.909           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.404           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.705           ms/op
ClientSimple.existUser:existUser·p0.99      sample          5.923           ms/op
ClientSimple.existUser:existUser·p0.999     sample         22.741           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         23.158           ms/op
ClientSimple.existUser:existUser·p1.00      sample         23.233           ms/op
ClientSimple.getUser                        sample  16999   1.881 ± 0.017   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.898           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.810           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.122           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.294           ms/op
ClientSimple.getUser:getUser·p0.99          sample          2.720           ms/op
ClientSimple.getUser:getUser·p0.999         sample         16.695           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         16.885           ms/op
ClientSimple.getUser:getUser·p1.00          sample         16.908           ms/op
ClientSimple.listUser                       sample  10055   3.174 ± 0.034   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.118           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.961           ms/op
ClientSimple.listUser:listUser·p0.90        sample          3.990           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.327           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.669           ms/op
ClientSimple.listUser:listUser·p0.999       sample         16.738           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         17.856           ms/op
ClientSimple.listUser:listUser·p1.00        sample         17.859           ms/op

Benchmark result is saved to 1711131046815.json
