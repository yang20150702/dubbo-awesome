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
# Warmup Iteration   1: 2.044 ops/ms
Iteration   1: 5.732 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.732 ops/ms


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
# Warmup Iteration   1: 5.443 ops/ms
Iteration   1: 10.060 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  10.060 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.938 ops/ms
Iteration   1: 7.933 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  7.933 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 1.997 ops/ms
Iteration   1: 3.950 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.950 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 5.828 ±(99.9%) 0.084 ms/op
Iteration   1: 3.103 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.103 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.386 ±(99.9%) 0.038 ms/op
Iteration   1: 2.062 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  2.062 ms/op


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
# Warmup Iteration   1: 4.690 ±(99.9%) 0.053 ms/op
Iteration   1: 3.092 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.092 ms/op


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
# Warmup Iteration   1: 11.398 ±(99.9%) 0.184 ms/op
Iteration   1: 8.527 ±(99.9%) 0.078 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.527 ms/op


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
# Warmup Iteration   1: 4.519 ±(99.9%) 0.105 ms/op
Iteration   1: 2.888 ±(99.9%) 0.043 ms/op
                 createUser·p0.00:   0.494 ms/op
                 createUser·p0.50:   2.576 ms/op
                 createUser·p0.90:   3.709 ms/op
                 createUser·p0.95:   4.202 ms/op
                 createUser·p0.99:   11.835 ms/op
                 createUser·p0.999:  15.565 ms/op
                 createUser·p0.9999: 16.535 ms/op
                 createUser·p1.00:   16.581 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 11063
  mean =      2.888 ±(99.9%) 0.043 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 10 
    [ 1.250,  2.500) = 4525 
    [ 2.500,  3.750) = 5458 
    [ 3.750,  5.000) = 794 
    [ 5.000,  6.250) = 67 
    [ 6.250,  7.500) = 63 
    [ 7.500,  8.750) = 18 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 29 
    [12.500, 13.750) = 44 
    [13.750, 15.000) = 29 
    [15.000, 16.250) = 25 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.494 ms/op
     p(50.0000) =      2.576 ms/op
     p(90.0000) =      3.709 ms/op
     p(95.0000) =      4.202 ms/op
     p(99.0000) =     11.835 ms/op
     p(99.9000) =     15.565 ms/op
     p(99.9900) =     16.535 ms/op
     p(99.9990) =     16.581 ms/op
     p(99.9999) =     16.581 ms/op
    p(100.0000) =     16.581 ms/op


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

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 3.070 ±(99.9%) 0.061 ms/op
Iteration   1: 2.015 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   0.454 ms/op
                 existUser·p0.50:   1.958 ms/op
                 existUser·p0.90:   2.474 ms/op
                 existUser·p0.95:   2.712 ms/op
                 existUser·p0.99:   3.560 ms/op
                 existUser·p0.999:  16.269 ms/op
                 existUser·p0.9999: 16.335 ms/op
                 existUser·p1.00:   16.335 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 15885
  mean =      2.015 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 414 
    [ 1.250,  2.500) = 14007 
    [ 2.500,  3.750) = 1367 
    [ 3.750,  5.000) = 25 
    [ 5.000,  6.250) = 12 
    [ 6.250,  7.500) = 22 
    [ 7.500,  8.750) = 6 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 10 
    [16.250, 17.500) = 22 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.454 ms/op
     p(50.0000) =      1.958 ms/op
     p(90.0000) =      2.474 ms/op
     p(95.0000) =      2.712 ms/op
     p(99.0000) =      3.560 ms/op
     p(99.9000) =     16.269 ms/op
     p(99.9900) =     16.335 ms/op
     p(99.9990) =     16.335 ms/op
     p(99.9999) =     16.335 ms/op
    p(100.0000) =     16.335 ms/op


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

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 4.304 ±(99.9%) 0.105 ms/op
Iteration   1: 3.261 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   0.769 ms/op
                 getUser·p0.50:   3.150 ms/op
                 getUser·p0.90:   4.018 ms/op
                 getUser·p0.95:   4.325 ms/op
                 getUser·p0.99:   6.426 ms/op
                 getUser·p0.999:  7.131 ms/op
                 getUser·p0.9999: 8.323 ms/op
                 getUser·p1.00:   8.323 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 9827
  mean =      3.261 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 1 
    [1.000, 1.500) = 15 
    [1.500, 2.000) = 31 
    [2.000, 2.500) = 722 
    [2.500, 3.000) = 3033 
    [3.000, 3.500) = 3285 
    [3.500, 4.000) = 1718 
    [4.000, 4.500) = 614 
    [4.500, 5.000) = 132 
    [5.000, 5.500) = 71 
    [5.500, 6.000) = 60 
    [6.000, 6.500) = 56 
    [6.500, 7.000) = 64 
    [7.000, 7.500) = 23 
    [7.500, 8.000) = 1 
    [8.000, 8.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.769 ms/op
     p(50.0000) =      3.150 ms/op
     p(90.0000) =      4.018 ms/op
     p(95.0000) =      4.325 ms/op
     p(99.0000) =      6.426 ms/op
     p(99.9000) =      7.131 ms/op
     p(99.9900) =      8.323 ms/op
     p(99.9990) =      8.323 ms/op
     p(99.9999) =      8.323 ms/op
    p(100.0000) =      8.323 ms/op


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

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 11.686 ±(99.9%) 0.379 ms/op
Iteration   1: 7.828 ±(99.9%) 0.112 ms/op
                 listUser·p0.00:   1.888 ms/op
                 listUser·p0.50:   7.487 ms/op
                 listUser·p0.90:   10.387 ms/op
                 listUser·p0.95:   11.469 ms/op
                 listUser·p0.99:   14.875 ms/op
                 listUser·p0.999:  20.120 ms/op
                 listUser·p0.9999: 24.019 ms/op
                 listUser·p1.00:   24.019 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 4077
  mean =      7.828 ±(99.9%) 0.112 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10 
    [ 2.500,  5.000) = 202 
    [ 5.000,  7.500) = 1841 
    [ 7.500, 10.000) = 1495 
    [10.000, 12.500) = 436 
    [12.500, 15.000) = 54 
    [15.000, 17.500) = 9 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.888 ms/op
     p(50.0000) =      7.487 ms/op
     p(90.0000) =     10.387 ms/op
     p(95.0000) =     11.469 ms/op
     p(99.0000) =     14.875 ms/op
     p(99.9000) =     20.120 ms/op
     p(99.9900) =     24.019 ms/op
     p(99.9990) =     24.019 ms/op
     p(99.9999) =     24.019 ms/op
    p(100.0000) =     24.019 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.732          ops/ms
Client.existUser                       thrpt         10.060          ops/ms
Client.getUser                         thrpt          7.933          ops/ms
Client.listUser                        thrpt          3.950          ops/ms
Client.createUser                       avgt          3.103           ms/op
Client.existUser                        avgt          2.062           ms/op
Client.getUser                          avgt          3.092           ms/op
Client.listUser                         avgt          8.527           ms/op
Client.createUser                     sample  11063   2.888 ± 0.043   ms/op
Client.createUser:createUser·p0.00    sample          0.494           ms/op
Client.createUser:createUser·p0.50    sample          2.576           ms/op
Client.createUser:createUser·p0.90    sample          3.709           ms/op
Client.createUser:createUser·p0.95    sample          4.202           ms/op
Client.createUser:createUser·p0.99    sample         11.835           ms/op
Client.createUser:createUser·p0.999   sample         15.565           ms/op
Client.createUser:createUser·p0.9999  sample         16.535           ms/op
Client.createUser:createUser·p1.00    sample         16.581           ms/op
Client.existUser                      sample  15885   2.015 ± 0.021   ms/op
Client.existUser:existUser·p0.00      sample          0.454           ms/op
Client.existUser:existUser·p0.50      sample          1.958           ms/op
Client.existUser:existUser·p0.90      sample          2.474           ms/op
Client.existUser:existUser·p0.95      sample          2.712           ms/op
Client.existUser:existUser·p0.99      sample          3.560           ms/op
Client.existUser:existUser·p0.999     sample         16.269           ms/op
Client.existUser:existUser·p0.9999    sample         16.335           ms/op
Client.existUser:existUser·p1.00      sample         16.335           ms/op
Client.getUser                        sample   9827   3.261 ± 0.024   ms/op
Client.getUser:getUser·p0.00          sample          0.769           ms/op
Client.getUser:getUser·p0.50          sample          3.150           ms/op
Client.getUser:getUser·p0.90          sample          4.018           ms/op
Client.getUser:getUser·p0.95          sample          4.325           ms/op
Client.getUser:getUser·p0.99          sample          6.426           ms/op
Client.getUser:getUser·p0.999         sample          7.131           ms/op
Client.getUser:getUser·p0.9999        sample          8.323           ms/op
Client.getUser:getUser·p1.00          sample          8.323           ms/op
Client.listUser                       sample   4077   7.828 ± 0.112   ms/op
Client.listUser:listUser·p0.00        sample          1.888           ms/op
Client.listUser:listUser·p0.50        sample          7.487           ms/op
Client.listUser:listUser·p0.90        sample         10.387           ms/op
Client.listUser:listUser·p0.95        sample         11.469           ms/op
Client.listUser:listUser·p0.99        sample         14.875           ms/op
Client.listUser:listUser·p0.999       sample         20.120           ms/op
Client.listUser:listUser·p0.9999      sample         24.019           ms/op
Client.listUser:listUser·p1.00        sample         24.019           ms/op
