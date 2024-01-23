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
# Warmup Iteration   1: 2.254 ops/ms
Iteration   1: 5.831 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.831 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:16
# Fork: 1 of 1
# Warmup Iteration   1: 5.887 ops/ms
Iteration   1: 12.188 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  12.188 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.831 ops/ms
Iteration   1: 7.745 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  7.745 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:02
# Fork: 1 of 1
# Warmup Iteration   1: 2.112 ops/ms
Iteration   1: 3.572 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.572 ops/ms


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
# Warmup Iteration   1: 5.705 ±(99.9%) 0.086 ms/op
Iteration   1: 3.176 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.176 ms/op


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
# Warmup Iteration   1: 3.067 ±(99.9%) 0.034 ms/op
Iteration   1: 1.835 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.835 ms/op


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
# Warmup Iteration   1: 5.347 ±(99.9%) 0.058 ms/op
Iteration   1: 3.131 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.131 ms/op


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
# Warmup Iteration   1: 13.523 ±(99.9%) 0.326 ms/op
Iteration   1: 8.815 ±(99.9%) 0.078 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.815 ms/op


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
# Warmup Iteration   1: 5.156 ±(99.9%) 0.103 ms/op
Iteration   1: 2.985 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   1.282 ms/op
                 createUser·p0.50:   2.822 ms/op
                 createUser·p0.90:   3.744 ms/op
                 createUser·p0.95:   4.121 ms/op
                 createUser·p0.99:   5.176 ms/op
                 createUser·p0.999:  7.535 ms/op
                 createUser·p0.9999: 9.129 ms/op
                 createUser·p1.00:   9.142 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10716
  mean =      2.985 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [ 1.000,  1.500) = 8 
    [ 1.500,  2.000) = 46 
    [ 2.000,  2.500) = 1385 
    [ 2.500,  3.000) = 5549 
    [ 3.000,  3.500) = 2228 
    [ 3.500,  4.000) = 842 
    [ 4.000,  4.500) = 395 
    [ 4.500,  5.000) = 130 
    [ 5.000,  5.500) = 42 
    [ 5.500,  6.000) = 18 
    [ 6.000,  6.500) = 32 
    [ 6.500,  7.000) = 6 
    [ 7.000,  7.500) = 22 
    [ 7.500,  8.000) = 8 
    [ 8.000,  8.500) = 2 
    [ 8.500,  9.000) = 2 
    [ 9.000,  9.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.282 ms/op
     p(50.0000) =      2.822 ms/op
     p(90.0000) =      3.744 ms/op
     p(95.0000) =      4.121 ms/op
     p(99.0000) =      5.176 ms/op
     p(99.9000) =      7.535 ms/op
     p(99.9900) =      9.129 ms/op
     p(99.9990) =      9.142 ms/op
     p(99.9999) =      9.142 ms/op
    p(100.0000) =      9.142 ms/op


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
# Warmup Iteration   1: 3.404 ±(99.9%) 0.149 ms/op
Iteration   1: 1.945 ±(99.9%) 0.024 ms/op
                 existUser·p0.00:   0.568 ms/op
                 existUser·p0.50:   1.819 ms/op
                 existUser·p0.90:   2.580 ms/op
                 existUser·p0.95:   2.847 ms/op
                 existUser·p0.99:   4.334 ms/op
                 existUser·p0.999:  17.367 ms/op
                 existUser·p0.9999: 17.502 ms/op
                 existUser·p1.00:   17.629 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 16479
  mean =      1.945 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 874 
    [ 1.250,  2.500) = 13518 
    [ 2.500,  3.750) = 1813 
    [ 3.750,  5.000) = 153 
    [ 5.000,  6.250) = 35 
    [ 6.250,  7.500) = 53 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 31 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.568 ms/op
     p(50.0000) =      1.819 ms/op
     p(90.0000) =      2.580 ms/op
     p(95.0000) =      2.847 ms/op
     p(99.0000) =      4.334 ms/op
     p(99.9000) =     17.367 ms/op
     p(99.9900) =     17.502 ms/op
     p(99.9990) =     17.629 ms/op
     p(99.9999) =     17.629 ms/op
    p(100.0000) =     17.629 ms/op


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
# Warmup Iteration   1: 4.849 ±(99.9%) 0.129 ms/op
Iteration   1: 3.031 ±(99.9%) 0.032 ms/op
                 getUser·p0.00:   1.061 ms/op
                 getUser·p0.50:   2.761 ms/op
                 getUser·p0.90:   3.908 ms/op
                 getUser·p0.95:   4.252 ms/op
                 getUser·p0.99:   5.923 ms/op
                 getUser·p0.999:  16.482 ms/op
                 getUser·p0.9999: 17.001 ms/op
                 getUser·p1.00:   17.007 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10598
  mean =      3.031 ±(99.9%) 0.032 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3 
    [ 1.250,  2.500) = 2352 
    [ 2.500,  3.750) = 6798 
    [ 3.750,  5.000) = 1300 
    [ 5.000,  6.250) = 49 
    [ 6.250,  7.500) = 40 
    [ 7.500,  8.750) = 19 
    [ 8.750, 10.000) = 5 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 12 
    [16.250, 17.500) = 19 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.061 ms/op
     p(50.0000) =      2.761 ms/op
     p(90.0000) =      3.908 ms/op
     p(95.0000) =      4.252 ms/op
     p(99.0000) =      5.923 ms/op
     p(99.9000) =     16.482 ms/op
     p(99.9900) =     17.001 ms/op
     p(99.9990) =     17.007 ms/op
     p(99.9999) =     17.007 ms/op
    p(100.0000) =     17.007 ms/op


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
# Warmup Iteration   1: 13.858 ±(99.9%) 0.503 ms/op
Iteration   1: 8.575 ±(99.9%) 0.133 ms/op
                 listUser·p0.00:   2.593 ms/op
                 listUser·p0.50:   8.176 ms/op
                 listUser·p0.90:   11.567 ms/op
                 listUser·p0.95:   13.156 ms/op
                 listUser·p0.99:   16.993 ms/op
                 listUser·p0.999:  21.847 ms/op
                 listUser·p0.9999: 26.083 ms/op
                 listUser·p1.00:   26.083 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3739
  mean =      8.575 ±(99.9%) 0.133 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 120 
    [ 5.000,  7.500) = 1267 
    [ 7.500, 10.000) = 1480 
    [10.000, 12.500) = 642 
    [12.500, 15.000) = 157 
    [15.000, 17.500) = 40 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      2.593 ms/op
     p(50.0000) =      8.176 ms/op
     p(90.0000) =     11.567 ms/op
     p(95.0000) =     13.156 ms/op
     p(99.0000) =     16.993 ms/op
     p(99.9000) =     21.847 ms/op
     p(99.9900) =     26.083 ms/op
     p(99.9990) =     26.083 ms/op
     p(99.9999) =     26.083 ms/op
    p(100.0000) =     26.083 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.831          ops/ms
Client.existUser                       thrpt         12.188          ops/ms
Client.getUser                         thrpt          7.745          ops/ms
Client.listUser                        thrpt          3.572          ops/ms
Client.createUser                       avgt          3.176           ms/op
Client.existUser                        avgt          1.835           ms/op
Client.getUser                          avgt          3.131           ms/op
Client.listUser                         avgt          8.815           ms/op
Client.createUser                     sample  10716   2.985 ± 0.020   ms/op
Client.createUser:createUser·p0.00    sample          1.282           ms/op
Client.createUser:createUser·p0.50    sample          2.822           ms/op
Client.createUser:createUser·p0.90    sample          3.744           ms/op
Client.createUser:createUser·p0.95    sample          4.121           ms/op
Client.createUser:createUser·p0.99    sample          5.176           ms/op
Client.createUser:createUser·p0.999   sample          7.535           ms/op
Client.createUser:createUser·p0.9999  sample          9.129           ms/op
Client.createUser:createUser·p1.00    sample          9.142           ms/op
Client.existUser                      sample  16479   1.945 ± 0.024   ms/op
Client.existUser:existUser·p0.00      sample          0.568           ms/op
Client.existUser:existUser·p0.50      sample          1.819           ms/op
Client.existUser:existUser·p0.90      sample          2.580           ms/op
Client.existUser:existUser·p0.95      sample          2.847           ms/op
Client.existUser:existUser·p0.99      sample          4.334           ms/op
Client.existUser:existUser·p0.999     sample         17.367           ms/op
Client.existUser:existUser·p0.9999    sample         17.502           ms/op
Client.existUser:existUser·p1.00      sample         17.629           ms/op
Client.getUser                        sample  10598   3.031 ± 0.032   ms/op
Client.getUser:getUser·p0.00          sample          1.061           ms/op
Client.getUser:getUser·p0.50          sample          2.761           ms/op
Client.getUser:getUser·p0.90          sample          3.908           ms/op
Client.getUser:getUser·p0.95          sample          4.252           ms/op
Client.getUser:getUser·p0.99          sample          5.923           ms/op
Client.getUser:getUser·p0.999         sample         16.482           ms/op
Client.getUser:getUser·p0.9999        sample         17.001           ms/op
Client.getUser:getUser·p1.00          sample         17.007           ms/op
Client.listUser                       sample   3739   8.575 ± 0.133   ms/op
Client.listUser:listUser·p0.00        sample          2.593           ms/op
Client.listUser:listUser·p0.50        sample          8.176           ms/op
Client.listUser:listUser·p0.90        sample         11.567           ms/op
Client.listUser:listUser·p0.95        sample         13.156           ms/op
Client.listUser:listUser·p0.99        sample         16.993           ms/op
Client.listUser:listUser·p0.999       sample         21.847           ms/op
Client.listUser:listUser·p0.9999      sample         26.083           ms/op
Client.listUser:listUser·p1.00        sample         26.083           ms/op
