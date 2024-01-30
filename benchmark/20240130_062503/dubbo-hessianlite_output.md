# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 2.326 ops/ms
Iteration   1: 5.413 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.413 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 5.097 ops/ms
Iteration   1: 11.519 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  11.519 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.783 ops/ms
Iteration   1: 8.545 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.545 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 2.149 ops/ms
Iteration   1: 3.715 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.715 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 33.33% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 5.776 ±(99.9%) 0.109 ms/op
Iteration   1: 3.392 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.392 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 41.67% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.331 ±(99.9%) 0.056 ms/op
Iteration   1: 2.173 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  2.173 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.988 ±(99.9%) 0.074 ms/op
Iteration   1: 3.204 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.204 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 13.222 ±(99.9%) 0.184 ms/op
Iteration   1: 8.647 ±(99.9%) 0.106 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.647 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 4.983 ±(99.9%) 0.116 ms/op
Iteration   1: 2.853 ±(99.9%) 0.027 ms/op
                 createUser·p0.00:   1.223 ms/op
                 createUser·p0.50:   2.634 ms/op
                 createUser·p0.90:   3.772 ms/op
                 createUser·p0.95:   4.276 ms/op
                 createUser·p0.99:   5.439 ms/op
                 createUser·p0.999:  13.206 ms/op
                 createUser·p0.9999: 13.285 ms/op
                 createUser·p1.00:   13.287 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 11199
  mean =      2.853 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 5 
    [ 1.250,  2.500) = 4429 
    [ 2.500,  3.750) = 5626 
    [ 3.750,  5.000) = 949 
    [ 5.000,  6.250) = 144 
    [ 6.250,  7.500) = 14 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 10 
    [12.500, 13.750) = 22 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.223 ms/op
     p(50.0000) =      2.634 ms/op
     p(90.0000) =      3.772 ms/op
     p(95.0000) =      4.276 ms/op
     p(99.0000) =      5.439 ms/op
     p(99.9000) =     13.206 ms/op
     p(99.9900) =     13.285 ms/op
     p(99.9990) =     13.287 ms/op
     p(99.9999) =     13.287 ms/op
    p(100.0000) =     13.287 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 75.00% complete, ETA 00:00:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.274 ±(99.9%) 0.082 ms/op
Iteration   1: 1.786 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   0.402 ms/op
                 existUser·p0.50:   1.673 ms/op
                 existUser·p0.90:   2.252 ms/op
                 existUser·p0.95:   2.560 ms/op
                 existUser·p0.99:   3.439 ms/op
                 existUser·p0.999:  13.337 ms/op
                 existUser·p0.9999: 13.602 ms/op
                 existUser·p1.00:   13.615 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 17950
  mean =      1.786 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 678 
    [ 1.250,  2.500) = 16207 
    [ 2.500,  3.750) = 955 
    [ 3.750,  5.000) = 47 
    [ 5.000,  6.250) = 30 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.402 ms/op
     p(50.0000) =      1.673 ms/op
     p(90.0000) =      2.252 ms/op
     p(95.0000) =      2.560 ms/op
     p(99.0000) =      3.439 ms/op
     p(99.9000) =     13.337 ms/op
     p(99.9900) =     13.602 ms/op
     p(99.9990) =     13.615 ms/op
     p(99.9999) =     13.615 ms/op
    p(100.0000) =     13.615 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 83.33% complete, ETA 00:00:13
# Fork: 1 of 1
# Warmup Iteration   1: 4.543 ±(99.9%) 0.099 ms/op
Iteration   1: 3.493 ±(99.9%) 0.025 ms/op
                 getUser·p0.00:   1.184 ms/op
                 getUser·p0.50:   3.482 ms/op
                 getUser·p0.90:   4.325 ms/op
                 getUser·p0.95:   4.596 ms/op
                 getUser·p0.99:   5.590 ms/op
                 getUser·p0.999:  7.376 ms/op
                 getUser·p0.9999: 7.791 ms/op
                 getUser·p1.00:   7.791 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 9163
  mean =      3.493 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [1.000, 1.500) = 15 
    [1.500, 2.000) = 86 
    [2.000, 2.500) = 636 
    [2.500, 3.000) = 1394 
    [3.000, 3.500) = 2559 
    [3.500, 4.000) = 2649 
    [4.000, 4.500) = 1240 
    [4.500, 5.000) = 365 
    [5.000, 5.500) = 112 
    [5.500, 6.000) = 33 
    [6.000, 6.500) = 19 
    [6.500, 7.000) = 30 
    [7.000, 7.500) = 18 

  Percentiles, ms/op:
      p(0.0000) =      1.184 ms/op
     p(50.0000) =      3.482 ms/op
     p(90.0000) =      4.325 ms/op
     p(95.0000) =      4.596 ms/op
     p(99.0000) =      5.590 ms/op
     p(99.9000) =      7.376 ms/op
     p(99.9900) =      7.791 ms/op
     p(99.9990) =      7.791 ms/op
     p(99.9999) =      7.791 ms/op
    p(100.0000) =      7.791 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 91.67% complete, ETA 00:00:06
# Fork: 1 of 1
# Warmup Iteration   1: 13.670 ±(99.9%) 0.428 ms/op
Iteration   1: 9.062 ±(99.9%) 0.144 ms/op
                 listUser·p0.00:   2.933 ms/op
                 listUser·p0.50:   8.700 ms/op
                 listUser·p0.90:   12.009 ms/op
                 listUser·p0.95:   13.897 ms/op
                 listUser·p0.99:   18.844 ms/op
                 listUser·p0.999:  24.460 ms/op
                 listUser·p0.9999: 25.461 ms/op
                 listUser·p1.00:   25.461 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3515
  mean =      9.062 ±(99.9%) 0.144 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 86 
    [ 5.000,  7.500) = 820 
    [ 7.500, 10.000) = 1644 
    [10.000, 12.500) = 680 
    [12.500, 15.000) = 177 
    [15.000, 17.500) = 61 
    [17.500, 20.000) = 27 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      2.933 ms/op
     p(50.0000) =      8.700 ms/op
     p(90.0000) =     12.009 ms/op
     p(95.0000) =     13.897 ms/op
     p(99.0000) =     18.844 ms/op
     p(99.9000) =     24.460 ms/op
     p(99.9900) =     25.461 ms/op
     p(99.9990) =     25.461 ms/op
     p(99.9999) =     25.461 ms/op
    p(100.0000) =     25.461 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.413          ops/ms
Client.existUser                       thrpt         11.519          ops/ms
Client.getUser                         thrpt          8.545          ops/ms
Client.listUser                        thrpt          3.715          ops/ms
Client.createUser                       avgt          3.392           ms/op
Client.existUser                        avgt          2.173           ms/op
Client.getUser                          avgt          3.204           ms/op
Client.listUser                         avgt          8.647           ms/op
Client.createUser                     sample  11199   2.853 ± 0.027   ms/op
Client.createUser:createUser·p0.00    sample          1.223           ms/op
Client.createUser:createUser·p0.50    sample          2.634           ms/op
Client.createUser:createUser·p0.90    sample          3.772           ms/op
Client.createUser:createUser·p0.95    sample          4.276           ms/op
Client.createUser:createUser·p0.99    sample          5.439           ms/op
Client.createUser:createUser·p0.999   sample         13.206           ms/op
Client.createUser:createUser·p0.9999  sample         13.285           ms/op
Client.createUser:createUser·p1.00    sample         13.287           ms/op
Client.existUser                      sample  17950   1.786 ± 0.016   ms/op
Client.existUser:existUser·p0.00      sample          0.402           ms/op
Client.existUser:existUser·p0.50      sample          1.673           ms/op
Client.existUser:existUser·p0.90      sample          2.252           ms/op
Client.existUser:existUser·p0.95      sample          2.560           ms/op
Client.existUser:existUser·p0.99      sample          3.439           ms/op
Client.existUser:existUser·p0.999     sample         13.337           ms/op
Client.existUser:existUser·p0.9999    sample         13.602           ms/op
Client.existUser:existUser·p1.00      sample         13.615           ms/op
Client.getUser                        sample   9163   3.493 ± 0.025   ms/op
Client.getUser:getUser·p0.00          sample          1.184           ms/op
Client.getUser:getUser·p0.50          sample          3.482           ms/op
Client.getUser:getUser·p0.90          sample          4.325           ms/op
Client.getUser:getUser·p0.95          sample          4.596           ms/op
Client.getUser:getUser·p0.99          sample          5.590           ms/op
Client.getUser:getUser·p0.999         sample          7.376           ms/op
Client.getUser:getUser·p0.9999        sample          7.791           ms/op
Client.getUser:getUser·p1.00          sample          7.791           ms/op
Client.listUser                       sample   3515   9.062 ± 0.144   ms/op
Client.listUser:listUser·p0.00        sample          2.933           ms/op
Client.listUser:listUser·p0.50        sample          8.700           ms/op
Client.listUser:listUser·p0.90        sample         12.009           ms/op
Client.listUser:listUser·p0.95        sample         13.897           ms/op
Client.listUser:listUser·p0.99        sample         18.844           ms/op
Client.listUser:listUser·p0.999       sample         24.460           ms/op
Client.listUser:listUser·p0.9999      sample         25.461           ms/op
Client.listUser:listUser·p1.00        sample         25.461           ms/op
