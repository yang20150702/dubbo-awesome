# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 2.536 ops/ms
Iteration   1: 6.522 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.522 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.150 ops/ms
Iteration   1: 12.818 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  12.818 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 16.67% complete, ETA 00:01:09
# Fork: 1 of 1
# Warmup Iteration   1: 4.766 ops/ms
Iteration   1: 9.610 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  9.610 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 25.00% complete, ETA 00:01:02
# Fork: 1 of 1
# Warmup Iteration   1: 2.281 ops/ms
Iteration   1: 3.723 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.723 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 33.33% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 5.376 ±(99.9%) 0.074 ms/op
Iteration   1: 2.941 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.941 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 41.67% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.989 ±(99.9%) 0.039 ms/op
Iteration   1: 2.178 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  2.178 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.383 ±(99.9%) 0.047 ms/op
Iteration   1: 3.095 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.095 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 13.312 ±(99.9%) 0.222 ms/op
Iteration   1: 8.446 ±(99.9%) 0.096 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.446 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 4.851 ±(99.9%) 0.101 ms/op
Iteration   1: 3.094 ±(99.9%) 0.023 ms/op
                 createUser·p0.00:   1.331 ms/op
                 createUser·p0.50:   3.002 ms/op
                 createUser·p0.90:   3.912 ms/op
                 createUser·p0.95:   4.202 ms/op
                 createUser·p0.99:   5.751 ms/op
                 createUser·p0.999:  8.552 ms/op
                 createUser·p0.9999: 8.942 ms/op
                 createUser·p1.00:   8.946 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10329
  mean =      3.094 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [1.000, 1.500) = 2 
    [1.500, 2.000) = 87 
    [2.000, 2.500) = 1749 
    [2.500, 3.000) = 3312 
    [3.000, 3.500) = 2881 
    [3.500, 4.000) = 1450 
    [4.000, 4.500) = 580 
    [4.500, 5.000) = 121 
    [5.000, 5.500) = 37 
    [5.500, 6.000) = 16 
    [6.000, 6.500) = 30 
    [6.500, 7.000) = 6 
    [7.000, 7.500) = 29 
    [7.500, 8.000) = 5 
    [8.000, 8.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      1.331 ms/op
     p(50.0000) =      3.002 ms/op
     p(90.0000) =      3.912 ms/op
     p(95.0000) =      4.202 ms/op
     p(99.0000) =      5.751 ms/op
     p(99.9000) =      8.552 ms/op
     p(99.9900) =      8.942 ms/op
     p(99.9990) =      8.946 ms/op
     p(99.9999) =      8.946 ms/op
    p(100.0000) =      8.946 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 75.00% complete, ETA 00:00:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.300 ±(99.9%) 0.078 ms/op
Iteration   1: 2.099 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.722 ms/op
                 existUser·p0.50:   2.062 ms/op
                 existUser·p0.90:   2.572 ms/op
                 existUser·p0.95:   2.798 ms/op
                 existUser·p0.99:   4.105 ms/op
                 existUser·p0.999:  5.372 ms/op
                 existUser·p0.9999: 5.749 ms/op
                 existUser·p1.00:   5.988 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 15225
  mean =      2.099 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 38 
    [1.000, 1.500) = 891 
    [1.500, 2.000) = 5777 
    [2.000, 2.500) = 6634 
    [2.500, 3.000) = 1358 
    [3.000, 3.500) = 217 
    [3.500, 4.000) = 130 
    [4.000, 4.500) = 60 
    [4.500, 5.000) = 50 
    [5.000, 5.500) = 66 

  Percentiles, ms/op:
      p(0.0000) =      0.722 ms/op
     p(50.0000) =      2.062 ms/op
     p(90.0000) =      2.572 ms/op
     p(95.0000) =      2.798 ms/op
     p(99.0000) =      4.105 ms/op
     p(99.9000) =      5.372 ms/op
     p(99.9900) =      5.749 ms/op
     p(99.9990) =      5.988 ms/op
     p(99.9999) =      5.988 ms/op
    p(100.0000) =      5.988 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 83.33% complete, ETA 00:00:13
# Fork: 1 of 1
# Warmup Iteration   1: 4.412 ±(99.9%) 0.104 ms/op
Iteration   1: 3.029 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   0.550 ms/op
                 getUser·p0.50:   3.002 ms/op
                 getUser·p0.90:   3.715 ms/op
                 getUser·p0.95:   4.006 ms/op
                 getUser·p0.99:   5.404 ms/op
                 getUser·p0.999:  7.033 ms/op
                 getUser·p0.9999: 8.964 ms/op
                 getUser·p1.00:   8.995 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10535
  mean =      3.029 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 13 
    [1.000, 1.500) = 37 
    [1.500, 2.000) = 419 
    [2.000, 2.500) = 1469 
    [2.500, 3.000) = 3325 
    [3.000, 3.500) = 3352 
    [3.500, 4.000) = 1380 
    [4.000, 4.500) = 342 
    [4.500, 5.000) = 39 
    [5.000, 5.500) = 72 
    [5.500, 6.000) = 30 
    [6.000, 6.500) = 20 
    [6.500, 7.000) = 24 
    [7.000, 7.500) = 10 
    [7.500, 8.000) = 1 
    [8.000, 8.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.550 ms/op
     p(50.0000) =      3.002 ms/op
     p(90.0000) =      3.715 ms/op
     p(95.0000) =      4.006 ms/op
     p(99.0000) =      5.404 ms/op
     p(99.9000) =      7.033 ms/op
     p(99.9900) =      8.964 ms/op
     p(99.9990) =      8.995 ms/op
     p(99.9999) =      8.995 ms/op
    p(100.0000) =      8.995 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 91.67% complete, ETA 00:00:06
# Fork: 1 of 1
# Warmup Iteration   1: 11.774 ±(99.9%) 0.398 ms/op
Iteration   1: 8.416 ±(99.9%) 0.137 ms/op
                 listUser·p0.00:   2.376 ms/op
                 listUser·p0.50:   8.045 ms/op
                 listUser·p0.90:   11.354 ms/op
                 listUser·p0.95:   12.302 ms/op
                 listUser·p0.99:   17.726 ms/op
                 listUser·p0.999:  25.755 ms/op
                 listUser·p0.9999: 27.230 ms/op
                 listUser·p1.00:   27.230 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3802
  mean =      8.416 ±(99.9%) 0.137 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1 
    [ 2.500,  5.000) = 184 
    [ 5.000,  7.500) = 1286 
    [ 7.500, 10.000) = 1437 
    [10.000, 12.500) = 718 
    [12.500, 15.000) = 121 
    [15.000, 17.500) = 14 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      2.376 ms/op
     p(50.0000) =      8.045 ms/op
     p(90.0000) =     11.354 ms/op
     p(95.0000) =     12.302 ms/op
     p(99.0000) =     17.726 ms/op
     p(99.9000) =     25.755 ms/op
     p(99.9900) =     27.230 ms/op
     p(99.9990) =     27.230 ms/op
     p(99.9999) =     27.230 ms/op
    p(100.0000) =     27.230 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.522          ops/ms
Client.existUser                       thrpt         12.818          ops/ms
Client.getUser                         thrpt          9.610          ops/ms
Client.listUser                        thrpt          3.723          ops/ms
Client.createUser                       avgt          2.941           ms/op
Client.existUser                        avgt          2.178           ms/op
Client.getUser                          avgt          3.095           ms/op
Client.listUser                         avgt          8.446           ms/op
Client.createUser                     sample  10329   3.094 ± 0.023   ms/op
Client.createUser:createUser·p0.00    sample          1.331           ms/op
Client.createUser:createUser·p0.50    sample          3.002           ms/op
Client.createUser:createUser·p0.90    sample          3.912           ms/op
Client.createUser:createUser·p0.95    sample          4.202           ms/op
Client.createUser:createUser·p0.99    sample          5.751           ms/op
Client.createUser:createUser·p0.999   sample          8.552           ms/op
Client.createUser:createUser·p0.9999  sample          8.942           ms/op
Client.createUser:createUser·p1.00    sample          8.946           ms/op
Client.existUser                      sample  15225   2.099 ± 0.013   ms/op
Client.existUser:existUser·p0.00      sample          0.722           ms/op
Client.existUser:existUser·p0.50      sample          2.062           ms/op
Client.existUser:existUser·p0.90      sample          2.572           ms/op
Client.existUser:existUser·p0.95      sample          2.798           ms/op
Client.existUser:existUser·p0.99      sample          4.105           ms/op
Client.existUser:existUser·p0.999     sample          5.372           ms/op
Client.existUser:existUser·p0.9999    sample          5.749           ms/op
Client.existUser:existUser·p1.00      sample          5.988           ms/op
Client.getUser                        sample  10535   3.029 ± 0.022   ms/op
Client.getUser:getUser·p0.00          sample          0.550           ms/op
Client.getUser:getUser·p0.50          sample          3.002           ms/op
Client.getUser:getUser·p0.90          sample          3.715           ms/op
Client.getUser:getUser·p0.95          sample          4.006           ms/op
Client.getUser:getUser·p0.99          sample          5.404           ms/op
Client.getUser:getUser·p0.999         sample          7.033           ms/op
Client.getUser:getUser·p0.9999        sample          8.964           ms/op
Client.getUser:getUser·p1.00          sample          8.995           ms/op
Client.listUser                       sample   3802   8.416 ± 0.137   ms/op
Client.listUser:listUser·p0.00        sample          2.376           ms/op
Client.listUser:listUser·p0.50        sample          8.045           ms/op
Client.listUser:listUser·p0.90        sample         11.354           ms/op
Client.listUser:listUser·p0.95        sample         12.302           ms/op
Client.listUser:listUser·p0.99        sample         17.726           ms/op
Client.listUser:listUser·p0.999       sample         25.755           ms/op
Client.listUser:listUser·p0.9999      sample         27.230           ms/op
Client.listUser:listUser·p1.00        sample         27.230           ms/op
