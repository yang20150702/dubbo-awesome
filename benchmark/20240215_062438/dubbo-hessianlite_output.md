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
# Warmup Iteration   1: 2.485 ops/ms
Iteration   1: 6.076 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.076 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.490 ops/ms
Iteration   1: 11.399 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  11.399 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:08
# Fork: 1 of 1
# Warmup Iteration   1: 4.641 ops/ms
Iteration   1: 9.439 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  9.439 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:01
# Fork: 1 of 1
# Warmup Iteration   1: 2.153 ops/ms
Iteration   1: 3.524 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.524 ops/ms


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
# Warmup Iteration   1: 5.245 ±(99.9%) 0.076 ms/op
Iteration   1: 3.173 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.173 ms/op


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
# Warmup Iteration   1: 3.395 ±(99.9%) 0.033 ms/op
Iteration   1: 1.988 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.988 ms/op


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
# Warmup Iteration   1: 4.787 ±(99.9%) 0.059 ms/op
Iteration   1: 3.365 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.365 ms/op


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
# Warmup Iteration   1: 11.866 ±(99.9%) 0.164 ms/op
Iteration   1: 7.463 ±(99.9%) 0.081 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  7.463 ms/op


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
# Warmup Iteration   1: 5.120 ±(99.9%) 0.110 ms/op
Iteration   1: 2.947 ±(99.9%) 0.031 ms/op
                 createUser·p0.00:   1.225 ms/op
                 createUser·p0.50:   2.855 ms/op
                 createUser·p0.90:   3.736 ms/op
                 createUser·p0.95:   4.010 ms/op
                 createUser·p0.99:   6.258 ms/op
                 createUser·p0.999:  15.385 ms/op
                 createUser·p0.9999: 15.514 ms/op
                 createUser·p1.00:   15.516 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10850
  mean =      2.947 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1 
    [ 1.250,  2.500) = 3200 
    [ 2.500,  3.750) = 6602 
    [ 3.750,  5.000) = 912 
    [ 5.000,  6.250) = 27 
    [ 6.250,  7.500) = 40 
    [ 7.500,  8.750) = 36 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 7 
    [15.000, 16.250) = 25 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.225 ms/op
     p(50.0000) =      2.855 ms/op
     p(90.0000) =      3.736 ms/op
     p(95.0000) =      4.010 ms/op
     p(99.0000) =      6.258 ms/op
     p(99.9000) =     15.385 ms/op
     p(99.9900) =     15.514 ms/op
     p(99.9990) =     15.516 ms/op
     p(99.9999) =     15.516 ms/op
    p(100.0000) =     15.516 ms/op


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
# Warmup Iteration   1: 3.191 ±(99.9%) 0.069 ms/op
Iteration   1: 1.859 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   0.327 ms/op
                 existUser·p0.50:   1.786 ms/op
                 existUser·p0.90:   2.310 ms/op
                 existUser·p0.95:   2.474 ms/op
                 existUser·p0.99:   3.889 ms/op
                 existUser·p0.999:  12.763 ms/op
                 existUser·p0.9999: 13.729 ms/op
                 existUser·p1.00:   13.812 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 17242
  mean =      1.859 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 859 
    [ 1.250,  2.500) = 15590 
    [ 2.500,  3.750) = 611 
    [ 3.750,  5.000) = 81 
    [ 5.000,  6.250) = 47 
    [ 6.250,  7.500) = 15 
    [ 7.500,  8.750) = 7 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 31 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.327 ms/op
     p(50.0000) =      1.786 ms/op
     p(90.0000) =      2.310 ms/op
     p(95.0000) =      2.474 ms/op
     p(99.0000) =      3.889 ms/op
     p(99.9000) =     12.763 ms/op
     p(99.9900) =     13.729 ms/op
     p(99.9990) =     13.812 ms/op
     p(99.9999) =     13.812 ms/op
    p(100.0000) =     13.812 ms/op


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
# Warmup Iteration   1: 4.716 ±(99.9%) 0.116 ms/op
Iteration   1: 3.249 ±(99.9%) 0.097 ms/op
                 getUser·p0.00:   1.033 ms/op
                 getUser·p0.50:   3.056 ms/op
                 getUser·p0.90:   3.867 ms/op
                 getUser·p0.95:   4.276 ms/op
                 getUser·p0.99:   5.890 ms/op
                 getUser·p0.999:  58.884 ms/op
                 getUser·p0.9999: 61.014 ms/op
                 getUser·p1.00:   61.014 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 9834
  mean =      3.249 ±(99.9%) 0.097 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 9579 
    [ 5.000, 10.000) = 207 
    [10.000, 15.000) = 2 
    [15.000, 20.000) = 4 
    [20.000, 25.000) = 3 
    [25.000, 30.000) = 7 
    [30.000, 35.000) = 5 
    [35.000, 40.000) = 3 
    [40.000, 45.000) = 3 
    [45.000, 50.000) = 5 
    [50.000, 55.000) = 2 
    [55.000, 60.000) = 10 
    [60.000, 65.000) = 4 

  Percentiles, ms/op:
      p(0.0000) =      1.033 ms/op
     p(50.0000) =      3.056 ms/op
     p(90.0000) =      3.867 ms/op
     p(95.0000) =      4.276 ms/op
     p(99.0000) =      5.890 ms/op
     p(99.9000) =     58.884 ms/op
     p(99.9900) =     61.014 ms/op
     p(99.9990) =     61.014 ms/op
     p(99.9999) =     61.014 ms/op
    p(100.0000) =     61.014 ms/op


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
# Warmup Iteration   1: 11.711 ±(99.9%) 0.454 ms/op
Iteration   1: 8.781 ±(99.9%) 0.127 ms/op
                 listUser·p0.00:   2.748 ms/op
                 listUser·p0.50:   8.298 ms/op
                 listUser·p0.90:   11.688 ms/op
                 listUser·p0.95:   13.299 ms/op
                 listUser·p0.99:   17.345 ms/op
                 listUser·p0.999:  21.442 ms/op
                 listUser·p0.9999: 21.561 ms/op
                 listUser·p1.00:   21.561 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3645
  mean =      8.781 ±(99.9%) 0.127 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 55 
    [ 5.000,  7.500) = 978 
    [ 7.500, 10.000) = 1792 
    [10.000, 12.500) = 581 
    [12.500, 15.000) = 172 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.748 ms/op
     p(50.0000) =      8.298 ms/op
     p(90.0000) =     11.688 ms/op
     p(95.0000) =     13.299 ms/op
     p(99.0000) =     17.345 ms/op
     p(99.9000) =     21.442 ms/op
     p(99.9900) =     21.561 ms/op
     p(99.9990) =     21.561 ms/op
     p(99.9999) =     21.561 ms/op
    p(100.0000) =     21.561 ms/op


# Run complete. Total time: 00:01:22

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.076          ops/ms
Client.existUser                       thrpt         11.399          ops/ms
Client.getUser                         thrpt          9.439          ops/ms
Client.listUser                        thrpt          3.524          ops/ms
Client.createUser                       avgt          3.173           ms/op
Client.existUser                        avgt          1.988           ms/op
Client.getUser                          avgt          3.365           ms/op
Client.listUser                         avgt          7.463           ms/op
Client.createUser                     sample  10850   2.947 ± 0.031   ms/op
Client.createUser:createUser·p0.00    sample          1.225           ms/op
Client.createUser:createUser·p0.50    sample          2.855           ms/op
Client.createUser:createUser·p0.90    sample          3.736           ms/op
Client.createUser:createUser·p0.95    sample          4.010           ms/op
Client.createUser:createUser·p0.99    sample          6.258           ms/op
Client.createUser:createUser·p0.999   sample         15.385           ms/op
Client.createUser:createUser·p0.9999  sample         15.514           ms/op
Client.createUser:createUser·p1.00    sample         15.516           ms/op
Client.existUser                      sample  17242   1.859 ± 0.017   ms/op
Client.existUser:existUser·p0.00      sample          0.327           ms/op
Client.existUser:existUser·p0.50      sample          1.786           ms/op
Client.existUser:existUser·p0.90      sample          2.310           ms/op
Client.existUser:existUser·p0.95      sample          2.474           ms/op
Client.existUser:existUser·p0.99      sample          3.889           ms/op
Client.existUser:existUser·p0.999     sample         12.763           ms/op
Client.existUser:existUser·p0.9999    sample         13.729           ms/op
Client.existUser:existUser·p1.00      sample         13.812           ms/op
Client.getUser                        sample   9834   3.249 ± 0.097   ms/op
Client.getUser:getUser·p0.00          sample          1.033           ms/op
Client.getUser:getUser·p0.50          sample          3.056           ms/op
Client.getUser:getUser·p0.90          sample          3.867           ms/op
Client.getUser:getUser·p0.95          sample          4.276           ms/op
Client.getUser:getUser·p0.99          sample          5.890           ms/op
Client.getUser:getUser·p0.999         sample         58.884           ms/op
Client.getUser:getUser·p0.9999        sample         61.014           ms/op
Client.getUser:getUser·p1.00          sample         61.014           ms/op
Client.listUser                       sample   3645   8.781 ± 0.127   ms/op
Client.listUser:listUser·p0.00        sample          2.748           ms/op
Client.listUser:listUser·p0.50        sample          8.298           ms/op
Client.listUser:listUser·p0.90        sample         11.688           ms/op
Client.listUser:listUser·p0.95        sample         13.299           ms/op
Client.listUser:listUser·p0.99        sample         17.345           ms/op
Client.listUser:listUser·p0.999       sample         21.442           ms/op
Client.listUser:listUser·p0.9999      sample         21.561           ms/op
Client.listUser:listUser·p1.00        sample         21.561           ms/op
