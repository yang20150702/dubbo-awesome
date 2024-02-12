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
# Warmup Iteration   1: 2.228 ops/ms
Iteration   1: 6.137 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.137 ops/ms


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
# Warmup Iteration   1: 6.591 ops/ms
Iteration   1: 12.651 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  12.651 ops/ms


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
# Warmup Iteration   1: 3.650 ops/ms
Iteration   1: 9.854 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  9.854 ops/ms


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
# Warmup Iteration   1: 2.371 ops/ms
Iteration   1: 3.793 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.793 ops/ms


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
# Warmup Iteration   1: 5.174 ±(99.9%) 0.062 ms/op
Iteration   1: 3.121 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.121 ms/op


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
# Warmup Iteration   1: 3.106 ±(99.9%) 0.039 ms/op
Iteration   1: 2.013 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  2.013 ms/op


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
# Warmup Iteration   1: 4.989 ±(99.9%) 0.058 ms/op
Iteration   1: 3.249 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.249 ms/op


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
# Warmup Iteration   1: 10.651 ±(99.9%) 0.183 ms/op
Iteration   1: 7.816 ±(99.9%) 0.053 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  7.816 ms/op


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
# Warmup Iteration   1: 5.201 ±(99.9%) 0.117 ms/op
Iteration   1: 3.302 ±(99.9%) 0.077 ms/op
                 createUser·p0.00:   1.016 ms/op
                 createUser·p0.50:   2.937 ms/op
                 createUser·p0.90:   3.949 ms/op
                 createUser·p0.95:   4.261 ms/op
                 createUser·p0.99:   13.027 ms/op
                 createUser·p0.999:  33.139 ms/op
                 createUser·p0.9999: 33.686 ms/op
                 createUser·p1.00:   33.686 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 9676
  mean =      3.302 ±(99.9%) 0.077 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1320 
    [ 2.500,  5.000) = 8075 
    [ 5.000,  7.500) = 102 
    [ 7.500, 10.000) = 19 
    [10.000, 12.500) = 49 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 5 
    [17.500, 20.000) = 37 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 30 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.016 ms/op
     p(50.0000) =      2.937 ms/op
     p(90.0000) =      3.949 ms/op
     p(95.0000) =      4.261 ms/op
     p(99.0000) =     13.027 ms/op
     p(99.9000) =     33.139 ms/op
     p(99.9900) =     33.686 ms/op
     p(99.9990) =     33.686 ms/op
     p(99.9999) =     33.686 ms/op
    p(100.0000) =     33.686 ms/op


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
# Warmup Iteration   1: 3.115 ±(99.9%) 0.056 ms/op
Iteration   1: 1.903 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.594 ms/op
                 existUser·p0.50:   1.853 ms/op
                 existUser·p0.90:   2.241 ms/op
                 existUser·p0.95:   2.425 ms/op
                 existUser·p0.99:   2.761 ms/op
                 existUser·p0.999:  4.519 ms/op
                 existUser·p0.9999: 6.034 ms/op
                 existUser·p1.00:   6.496 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 16796
  mean =      1.903 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 15 
    [1.000, 1.500) = 539 
    [1.500, 2.000) = 12039 
    [2.000, 2.500) = 3598 
    [2.500, 3.000) = 480 
    [3.000, 3.500) = 26 
    [3.500, 4.000) = 3 
    [4.000, 4.500) = 77 
    [4.500, 5.000) = 16 
    [5.000, 5.500) = 0 
    [5.500, 6.000) = 2 
    [6.000, 6.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.594 ms/op
     p(50.0000) =      1.853 ms/op
     p(90.0000) =      2.241 ms/op
     p(95.0000) =      2.425 ms/op
     p(99.0000) =      2.761 ms/op
     p(99.9000) =      4.519 ms/op
     p(99.9900) =      6.034 ms/op
     p(99.9990) =      6.496 ms/op
     p(99.9999) =      6.496 ms/op
    p(100.0000) =      6.496 ms/op


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
# Warmup Iteration   1: 5.045 ±(99.9%) 0.168 ms/op
Iteration   1: 2.964 ±(99.9%) 0.050 ms/op
                 getUser·p0.00:   0.794 ms/op
                 getUser·p0.50:   2.875 ms/op
                 getUser·p0.90:   3.621 ms/op
                 getUser·p0.95:   3.903 ms/op
                 getUser·p0.99:   7.070 ms/op
                 getUser·p0.999:  26.294 ms/op
                 getUser·p0.9999: 26.766 ms/op
                 getUser·p1.00:   26.771 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10788
  mean =      2.964 ±(99.9%) 0.050 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3318 
    [ 2.500,  5.000) = 7251 
    [ 5.000,  7.500) = 151 
    [ 7.500, 10.000) = 4 
    [10.000, 12.500) = 7 
    [12.500, 15.000) = 19 
    [15.000, 17.500) = 6 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.794 ms/op
     p(50.0000) =      2.875 ms/op
     p(90.0000) =      3.621 ms/op
     p(95.0000) =      3.903 ms/op
     p(99.0000) =      7.070 ms/op
     p(99.9000) =     26.294 ms/op
     p(99.9900) =     26.766 ms/op
     p(99.9990) =     26.771 ms/op
     p(99.9999) =     26.771 ms/op
    p(100.0000) =     26.771 ms/op


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
# Warmup Iteration   1: 12.978 ±(99.9%) 0.569 ms/op
Iteration   1: 7.522 ±(99.9%) 0.103 ms/op
                 listUser·p0.00:   2.367 ms/op
                 listUser·p0.50:   7.258 ms/op
                 listUser·p0.90:   9.732 ms/op
                 listUser·p0.95:   10.895 ms/op
                 listUser·p0.99:   16.420 ms/op
                 listUser·p0.999:  18.587 ms/op
                 listUser·p0.9999: 20.742 ms/op
                 listUser·p1.00:   20.742 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 4290
  mean =      7.522 ±(99.9%) 0.103 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2 
    [ 2.500,  5.000) = 267 
    [ 5.000,  7.500) = 2121 
    [ 7.500, 10.000) = 1546 
    [10.000, 12.500) = 248 
    [12.500, 15.000) = 47 
    [15.000, 17.500) = 43 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.367 ms/op
     p(50.0000) =      7.258 ms/op
     p(90.0000) =      9.732 ms/op
     p(95.0000) =     10.895 ms/op
     p(99.0000) =     16.420 ms/op
     p(99.9000) =     18.587 ms/op
     p(99.9900) =     20.742 ms/op
     p(99.9990) =     20.742 ms/op
     p(99.9999) =     20.742 ms/op
    p(100.0000) =     20.742 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.137          ops/ms
Client.existUser                       thrpt         12.651          ops/ms
Client.getUser                         thrpt          9.854          ops/ms
Client.listUser                        thrpt          3.793          ops/ms
Client.createUser                       avgt          3.121           ms/op
Client.existUser                        avgt          2.013           ms/op
Client.getUser                          avgt          3.249           ms/op
Client.listUser                         avgt          7.816           ms/op
Client.createUser                     sample   9676   3.302 ± 0.077   ms/op
Client.createUser:createUser·p0.00    sample          1.016           ms/op
Client.createUser:createUser·p0.50    sample          2.937           ms/op
Client.createUser:createUser·p0.90    sample          3.949           ms/op
Client.createUser:createUser·p0.95    sample          4.261           ms/op
Client.createUser:createUser·p0.99    sample         13.027           ms/op
Client.createUser:createUser·p0.999   sample         33.139           ms/op
Client.createUser:createUser·p0.9999  sample         33.686           ms/op
Client.createUser:createUser·p1.00    sample         33.686           ms/op
Client.existUser                      sample  16796   1.903 ± 0.008   ms/op
Client.existUser:existUser·p0.00      sample          0.594           ms/op
Client.existUser:existUser·p0.50      sample          1.853           ms/op
Client.existUser:existUser·p0.90      sample          2.241           ms/op
Client.existUser:existUser·p0.95      sample          2.425           ms/op
Client.existUser:existUser·p0.99      sample          2.761           ms/op
Client.existUser:existUser·p0.999     sample          4.519           ms/op
Client.existUser:existUser·p0.9999    sample          6.034           ms/op
Client.existUser:existUser·p1.00      sample          6.496           ms/op
Client.getUser                        sample  10788   2.964 ± 0.050   ms/op
Client.getUser:getUser·p0.00          sample          0.794           ms/op
Client.getUser:getUser·p0.50          sample          2.875           ms/op
Client.getUser:getUser·p0.90          sample          3.621           ms/op
Client.getUser:getUser·p0.95          sample          3.903           ms/op
Client.getUser:getUser·p0.99          sample          7.070           ms/op
Client.getUser:getUser·p0.999         sample         26.294           ms/op
Client.getUser:getUser·p0.9999        sample         26.766           ms/op
Client.getUser:getUser·p1.00          sample         26.771           ms/op
Client.listUser                       sample   4290   7.522 ± 0.103   ms/op
Client.listUser:listUser·p0.00        sample          2.367           ms/op
Client.listUser:listUser·p0.50        sample          7.258           ms/op
Client.listUser:listUser·p0.90        sample          9.732           ms/op
Client.listUser:listUser·p0.95        sample         10.895           ms/op
Client.listUser:listUser·p0.99        sample         16.420           ms/op
Client.listUser:listUser·p0.999       sample         18.587           ms/op
Client.listUser:listUser·p0.9999      sample         20.742           ms/op
Client.listUser:listUser·p1.00        sample         20.742           ms/op
