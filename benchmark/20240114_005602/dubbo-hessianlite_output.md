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
# Warmup Iteration   1: 2.579 ops/ms
Iteration   1: 6.246 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.246 ops/ms


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
# Warmup Iteration   1: 6.548 ops/ms
Iteration   1: 13.633 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  13.633 ops/ms


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
# Warmup Iteration   1: 4.055 ops/ms
Iteration   1: 8.859 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.859 ops/ms


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
# Warmup Iteration   1: 2.048 ops/ms
Iteration   1: 3.787 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.787 ops/ms


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
# Warmup Iteration   1: 5.352 ±(99.9%) 0.078 ms/op
Iteration   1: 3.026 ±(99.9%) 0.026 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.026 ms/op


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
# Warmup Iteration   1: 3.186 ±(99.9%) 0.033 ms/op
Iteration   1: 1.817 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.817 ms/op


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
# Warmup Iteration   1: 4.529 ±(99.9%) 0.056 ms/op
Iteration   1: 2.886 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  2.886 ms/op


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
# Warmup Iteration   1: 11.698 ±(99.9%) 0.235 ms/op
Iteration   1: 7.976 ±(99.9%) 0.077 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  7.976 ms/op


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
# Warmup Iteration   1: 5.033 ±(99.9%) 0.114 ms/op
Iteration   1: 3.060 ±(99.9%) 0.036 ms/op
                 createUser·p0.00:   1.176 ms/op
                 createUser·p0.50:   2.925 ms/op
                 createUser·p0.90:   3.523 ms/op
                 createUser·p0.95:   3.764 ms/op
                 createUser·p0.99:   9.257 ms/op
                 createUser·p0.999:  15.630 ms/op
                 createUser·p0.9999: 15.743 ms/op
                 createUser·p1.00:   15.745 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10450
  mean =      3.060 ±(99.9%) 0.036 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2 
    [ 1.250,  2.500) = 1497 
    [ 2.500,  3.750) = 8411 
    [ 3.750,  5.000) = 367 
    [ 5.000,  6.250) = 45 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 62 
    [10.000, 11.250) = 6 
    [11.250, 12.500) = 21 
    [12.500, 13.750) = 7 
    [13.750, 15.000) = 3 
    [15.000, 16.250) = 29 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.176 ms/op
     p(50.0000) =      2.925 ms/op
     p(90.0000) =      3.523 ms/op
     p(95.0000) =      3.764 ms/op
     p(99.0000) =      9.257 ms/op
     p(99.9000) =     15.630 ms/op
     p(99.9900) =     15.743 ms/op
     p(99.9990) =     15.745 ms/op
     p(99.9999) =     15.745 ms/op
    p(100.0000) =     15.745 ms/op


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
# Warmup Iteration   1: 2.909 ±(99.9%) 0.057 ms/op
Iteration   1: 1.879 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   0.664 ms/op
                 existUser·p0.50:   1.823 ms/op
                 existUser·p0.90:   2.323 ms/op
                 existUser·p0.95:   2.519 ms/op
                 existUser·p0.99:   2.934 ms/op
                 existUser·p0.999:  11.156 ms/op
                 existUser·p0.9999: 11.809 ms/op
                 existUser·p1.00:   11.878 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 17058
  mean =      1.879 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 414 
    [ 1.250,  2.500) = 15726 
    [ 2.500,  3.750) = 839 
    [ 3.750,  5.000) = 8 
    [ 5.000,  6.250) = 39 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 26 
    [11.250, 12.500) = 6 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.664 ms/op
     p(50.0000) =      1.823 ms/op
     p(90.0000) =      2.323 ms/op
     p(95.0000) =      2.519 ms/op
     p(99.0000) =      2.934 ms/op
     p(99.9000) =     11.156 ms/op
     p(99.9900) =     11.809 ms/op
     p(99.9990) =     11.878 ms/op
     p(99.9999) =     11.878 ms/op
    p(100.0000) =     11.878 ms/op


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
# Warmup Iteration   1: 4.746 ±(99.9%) 0.139 ms/op
Iteration   1: 3.018 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   0.778 ms/op
                 getUser·p0.50:   3.019 ms/op
                 getUser·p0.90:   3.736 ms/op
                 getUser·p0.95:   3.944 ms/op
                 getUser·p0.99:   5.153 ms/op
                 getUser·p0.999:  7.171 ms/op
                 getUser·p0.9999: 10.347 ms/op
                 getUser·p1.00:   10.371 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10589
  mean =      3.018 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 0.000,  1.000) = 2 
    [ 1.000,  2.000) = 465 
    [ 2.000,  3.000) = 4656 
    [ 3.000,  4.000) = 4991 
    [ 4.000,  5.000) = 355 
    [ 5.000,  6.000) = 65 
    [ 6.000,  7.000) = 42 
    [ 7.000,  8.000) = 9 
    [ 8.000,  9.000) = 1 
    [ 9.000, 10.000) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.778 ms/op
     p(50.0000) =      3.019 ms/op
     p(90.0000) =      3.736 ms/op
     p(95.0000) =      3.944 ms/op
     p(99.0000) =      5.153 ms/op
     p(99.9000) =      7.171 ms/op
     p(99.9900) =     10.347 ms/op
     p(99.9990) =     10.371 ms/op
     p(99.9999) =     10.371 ms/op
    p(100.0000) =     10.371 ms/op


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
# Warmup Iteration   1: 11.779 ±(99.9%) 0.436 ms/op
Iteration   1: 8.745 ±(99.9%) 0.153 ms/op
                 listUser·p0.00:   2.269 ms/op
                 listUser·p0.50:   8.339 ms/op
                 listUser·p0.90:   12.321 ms/op
                 listUser·p0.95:   13.500 ms/op
                 listUser·p0.99:   18.416 ms/op
                 listUser·p0.999:  22.066 ms/op
                 listUser·p0.9999: 25.625 ms/op
                 listUser·p1.00:   25.625 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3649
  mean =      8.745 ±(99.9%) 0.153 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3 
    [ 2.500,  5.000) = 172 
    [ 5.000,  7.500) = 1190 
    [ 7.500, 10.000) = 1230 
    [10.000, 12.500) = 727 
    [12.500, 15.000) = 243 
    [15.000, 17.500) = 38 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      2.269 ms/op
     p(50.0000) =      8.339 ms/op
     p(90.0000) =     12.321 ms/op
     p(95.0000) =     13.500 ms/op
     p(99.0000) =     18.416 ms/op
     p(99.9000) =     22.066 ms/op
     p(99.9900) =     25.625 ms/op
     p(99.9990) =     25.625 ms/op
     p(99.9999) =     25.625 ms/op
    p(100.0000) =     25.625 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.246          ops/ms
Client.existUser                       thrpt         13.633          ops/ms
Client.getUser                         thrpt          8.859          ops/ms
Client.listUser                        thrpt          3.787          ops/ms
Client.createUser                       avgt          3.026           ms/op
Client.existUser                        avgt          1.817           ms/op
Client.getUser                          avgt          2.886           ms/op
Client.listUser                         avgt          7.976           ms/op
Client.createUser                     sample  10450   3.060 ± 0.036   ms/op
Client.createUser:createUser·p0.00    sample          1.176           ms/op
Client.createUser:createUser·p0.50    sample          2.925           ms/op
Client.createUser:createUser·p0.90    sample          3.523           ms/op
Client.createUser:createUser·p0.95    sample          3.764           ms/op
Client.createUser:createUser·p0.99    sample          9.257           ms/op
Client.createUser:createUser·p0.999   sample         15.630           ms/op
Client.createUser:createUser·p0.9999  sample         15.743           ms/op
Client.createUser:createUser·p1.00    sample         15.745           ms/op
Client.existUser                      sample  17058   1.879 ± 0.014   ms/op
Client.existUser:existUser·p0.00      sample          0.664           ms/op
Client.existUser:existUser·p0.50      sample          1.823           ms/op
Client.existUser:existUser·p0.90      sample          2.323           ms/op
Client.existUser:existUser·p0.95      sample          2.519           ms/op
Client.existUser:existUser·p0.99      sample          2.934           ms/op
Client.existUser:existUser·p0.999     sample         11.156           ms/op
Client.existUser:existUser·p0.9999    sample         11.809           ms/op
Client.existUser:existUser·p1.00      sample         11.878           ms/op
Client.getUser                        sample  10589   3.018 ± 0.022   ms/op
Client.getUser:getUser·p0.00          sample          0.778           ms/op
Client.getUser:getUser·p0.50          sample          3.019           ms/op
Client.getUser:getUser·p0.90          sample          3.736           ms/op
Client.getUser:getUser·p0.95          sample          3.944           ms/op
Client.getUser:getUser·p0.99          sample          5.153           ms/op
Client.getUser:getUser·p0.999         sample          7.171           ms/op
Client.getUser:getUser·p0.9999        sample         10.347           ms/op
Client.getUser:getUser·p1.00          sample         10.371           ms/op
Client.listUser                       sample   3649   8.745 ± 0.153   ms/op
Client.listUser:listUser·p0.00        sample          2.269           ms/op
Client.listUser:listUser·p0.50        sample          8.339           ms/op
Client.listUser:listUser·p0.90        sample         12.321           ms/op
Client.listUser:listUser·p0.95        sample         13.500           ms/op
Client.listUser:listUser·p0.99        sample         18.416           ms/op
Client.listUser:listUser·p0.999       sample         22.066           ms/op
Client.listUser:listUser·p0.9999      sample         25.625           ms/op
Client.listUser:listUser·p1.00        sample         25.625           ms/op
