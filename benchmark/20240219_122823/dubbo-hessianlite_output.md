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
# Warmup Iteration   1: 2.211 ops/ms
Iteration   1: 6.136 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.136 ops/ms


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
# Warmup Iteration   1: 5.593 ops/ms
Iteration   1: 12.027 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  12.027 ops/ms


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
# Warmup Iteration   1: 4.171 ops/ms
Iteration   1: 8.543 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.543 ops/ms


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
# Warmup Iteration   1: 1.937 ops/ms
Iteration   1: 3.854 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.854 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 5.425 ±(99.9%) 0.062 ms/op
Iteration   1: 3.285 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.285 ms/op


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
# Warmup Iteration   1: 3.886 ±(99.9%) 0.064 ms/op
Iteration   1: 1.893 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.893 ms/op


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
# Warmup Iteration   1: 4.976 ±(99.9%) 0.060 ms/op
Iteration   1: 3.045 ±(99.9%) 0.024 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.045 ms/op


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
# Warmup Iteration   1: 12.804 ±(99.9%) 0.193 ms/op
Iteration   1: 8.488 ±(99.9%) 0.080 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.488 ms/op


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
# Warmup Iteration   1: 5.033 ±(99.9%) 0.131 ms/op
Iteration   1: 3.206 ±(99.9%) 0.028 ms/op
                 createUser·p0.00:   1.026 ms/op
                 createUser·p0.50:   3.072 ms/op
                 createUser·p0.90:   4.121 ms/op
                 createUser·p0.95:   4.432 ms/op
                 createUser·p0.99:   5.308 ms/op
                 createUser·p0.999:  12.206 ms/op
                 createUser·p0.9999: 12.419 ms/op
                 createUser·p1.00:   12.419 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 9959
  mean =      3.206 ±(99.9%) 0.028 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 5 
    [ 1.250,  2.500) = 1338 
    [ 2.500,  3.750) = 6654 
    [ 3.750,  5.000) = 1797 
    [ 5.000,  6.250) = 123 
    [ 6.250,  7.500) = 9 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.026 ms/op
     p(50.0000) =      3.072 ms/op
     p(90.0000) =      4.121 ms/op
     p(95.0000) =      4.432 ms/op
     p(99.0000) =      5.308 ms/op
     p(99.9000) =     12.206 ms/op
     p(99.9900) =     12.419 ms/op
     p(99.9990) =     12.419 ms/op
     p(99.9999) =     12.419 ms/op
    p(100.0000) =     12.419 ms/op


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

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 3.454 ±(99.9%) 0.072 ms/op
Iteration   1: 1.927 ±(99.9%) 0.029 ms/op
                 existUser·p0.00:   0.735 ms/op
                 existUser·p0.50:   1.757 ms/op
                 existUser·p0.90:   2.523 ms/op
                 existUser·p0.95:   2.707 ms/op
                 existUser·p0.99:   3.422 ms/op
                 existUser·p0.999:  24.794 ms/op
                 existUser·p0.9999: 25.823 ms/op
                 existUser·p1.00:   25.952 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 16585
  mean =      1.927 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14784 
    [ 2.500,  5.000) = 1736 
    [ 5.000,  7.500) = 31 
    [ 7.500, 10.000) = 2 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      0.735 ms/op
     p(50.0000) =      1.757 ms/op
     p(90.0000) =      2.523 ms/op
     p(95.0000) =      2.707 ms/op
     p(99.0000) =      3.422 ms/op
     p(99.9000) =     24.794 ms/op
     p(99.9900) =     25.823 ms/op
     p(99.9990) =     25.952 ms/op
     p(99.9999) =     25.952 ms/op
    p(100.0000) =     25.952 ms/op


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

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 4.728 ±(99.9%) 0.140 ms/op
Iteration   1: 2.940 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   0.675 ms/op
                 getUser·p0.50:   2.785 ms/op
                 getUser·p0.90:   3.887 ms/op
                 getUser·p0.95:   4.211 ms/op
                 getUser·p0.99:   4.719 ms/op
                 getUser·p0.999:  6.481 ms/op
                 getUser·p0.9999: 8.835 ms/op
                 getUser·p1.00:   8.864 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10990
  mean =      2.940 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 10 
    [1.000, 1.500) = 48 
    [1.500, 2.000) = 267 
    [2.000, 2.500) = 3250 
    [2.500, 3.000) = 2887 
    [3.000, 3.500) = 2134 
    [3.500, 4.000) = 1516 
    [4.000, 4.500) = 638 
    [4.500, 5.000) = 172 
    [5.000, 5.500) = 28 
    [5.500, 6.000) = 27 
    [6.000, 6.500) = 3 
    [6.500, 7.000) = 2 
    [7.000, 7.500) = 1 
    [7.500, 8.000) = 0 
    [8.000, 8.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.675 ms/op
     p(50.0000) =      2.785 ms/op
     p(90.0000) =      3.887 ms/op
     p(95.0000) =      4.211 ms/op
     p(99.0000) =      4.719 ms/op
     p(99.9000) =      6.481 ms/op
     p(99.9900) =      8.835 ms/op
     p(99.9990) =      8.864 ms/op
     p(99.9999) =      8.864 ms/op
    p(100.0000) =      8.864 ms/op


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

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 13.217 ±(99.9%) 0.571 ms/op
Iteration   1: 8.407 ±(99.9%) 0.269 ms/op
                 listUser·p0.00:   2.843 ms/op
                 listUser·p0.50:   7.602 ms/op
                 listUser·p0.90:   10.568 ms/op
                 listUser·p0.95:   12.321 ms/op
                 listUser·p0.99:   31.921 ms/op
                 listUser·p0.999:  61.970 ms/op
                 listUser·p0.9999: 74.187 ms/op
                 listUser·p1.00:   74.187 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3803
  mean =      8.407 ±(99.9%) 0.269 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 128 
    [ 5.000, 10.000) = 3149 
    [10.000, 15.000) = 401 
    [15.000, 20.000) = 70 
    [20.000, 25.000) = 13 
    [25.000, 30.000) = 4 
    [30.000, 35.000) = 7 
    [35.000, 40.000) = 2 
    [40.000, 45.000) = 3 
    [45.000, 50.000) = 5 
    [50.000, 55.000) = 1 
    [55.000, 60.000) = 11 
    [60.000, 65.000) = 7 
    [65.000, 70.000) = 0 
    [70.000, 75.000) = 2 

  Percentiles, ms/op:
      p(0.0000) =      2.843 ms/op
     p(50.0000) =      7.602 ms/op
     p(90.0000) =     10.568 ms/op
     p(95.0000) =     12.321 ms/op
     p(99.0000) =     31.921 ms/op
     p(99.9000) =     61.970 ms/op
     p(99.9900) =     74.187 ms/op
     p(99.9990) =     74.187 ms/op
     p(99.9999) =     74.187 ms/op
    p(100.0000) =     74.187 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.136          ops/ms
Client.existUser                       thrpt         12.027          ops/ms
Client.getUser                         thrpt          8.543          ops/ms
Client.listUser                        thrpt          3.854          ops/ms
Client.createUser                       avgt          3.285           ms/op
Client.existUser                        avgt          1.893           ms/op
Client.getUser                          avgt          3.045           ms/op
Client.listUser                         avgt          8.488           ms/op
Client.createUser                     sample   9959   3.206 ± 0.028   ms/op
Client.createUser:createUser·p0.00    sample          1.026           ms/op
Client.createUser:createUser·p0.50    sample          3.072           ms/op
Client.createUser:createUser·p0.90    sample          4.121           ms/op
Client.createUser:createUser·p0.95    sample          4.432           ms/op
Client.createUser:createUser·p0.99    sample          5.308           ms/op
Client.createUser:createUser·p0.999   sample         12.206           ms/op
Client.createUser:createUser·p0.9999  sample         12.419           ms/op
Client.createUser:createUser·p1.00    sample         12.419           ms/op
Client.existUser                      sample  16585   1.927 ± 0.029   ms/op
Client.existUser:existUser·p0.00      sample          0.735           ms/op
Client.existUser:existUser·p0.50      sample          1.757           ms/op
Client.existUser:existUser·p0.90      sample          2.523           ms/op
Client.existUser:existUser·p0.95      sample          2.707           ms/op
Client.existUser:existUser·p0.99      sample          3.422           ms/op
Client.existUser:existUser·p0.999     sample         24.794           ms/op
Client.existUser:existUser·p0.9999    sample         25.823           ms/op
Client.existUser:existUser·p1.00      sample         25.952           ms/op
Client.getUser                        sample  10990   2.940 ± 0.022   ms/op
Client.getUser:getUser·p0.00          sample          0.675           ms/op
Client.getUser:getUser·p0.50          sample          2.785           ms/op
Client.getUser:getUser·p0.90          sample          3.887           ms/op
Client.getUser:getUser·p0.95          sample          4.211           ms/op
Client.getUser:getUser·p0.99          sample          4.719           ms/op
Client.getUser:getUser·p0.999         sample          6.481           ms/op
Client.getUser:getUser·p0.9999        sample          8.835           ms/op
Client.getUser:getUser·p1.00          sample          8.864           ms/op
Client.listUser                       sample   3803   8.407 ± 0.269   ms/op
Client.listUser:listUser·p0.00        sample          2.843           ms/op
Client.listUser:listUser·p0.50        sample          7.602           ms/op
Client.listUser:listUser·p0.90        sample         10.568           ms/op
Client.listUser:listUser·p0.95        sample         12.321           ms/op
Client.listUser:listUser·p0.99        sample         31.921           ms/op
Client.listUser:listUser·p0.999       sample         61.970           ms/op
Client.listUser:listUser·p0.9999      sample         74.187           ms/op
Client.listUser:listUser·p1.00        sample         74.187           ms/op
