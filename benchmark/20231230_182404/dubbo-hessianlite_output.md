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
# Warmup Iteration   1: 2.326 ops/ms
Iteration   1: 5.792 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.792 ops/ms


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
# Warmup Iteration   1: 6.464 ops/ms
Iteration   1: 14.421 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  14.421 ops/ms


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
# Warmup Iteration   1: 4.759 ops/ms
Iteration   1: 9.978 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  9.978 ops/ms


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
# Warmup Iteration   1: 2.034 ops/ms
Iteration   1: 2.963 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  2.963 ops/ms


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
# Warmup Iteration   1: 5.316 ±(99.9%) 0.072 ms/op
Iteration   1: 3.230 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.230 ms/op


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
# Warmup Iteration   1: 3.720 ±(99.9%) 0.040 ms/op
Iteration   1: 1.907 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.907 ms/op


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
# Warmup Iteration   1: 4.207 ±(99.9%) 0.045 ms/op
Iteration   1: 3.278 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.278 ms/op


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
# Warmup Iteration   1: 12.466 ±(99.9%) 0.247 ms/op
Iteration   1: 8.150 ±(99.9%) 0.086 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.150 ms/op


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
# Warmup Iteration   1: 4.759 ±(99.9%) 0.098 ms/op
Iteration   1: 3.024 ±(99.9%) 0.029 ms/op
                 createUser·p0.00:   0.921 ms/op
                 createUser·p0.50:   2.814 ms/op
                 createUser·p0.90:   3.891 ms/op
                 createUser·p0.95:   4.440 ms/op
                 createUser·p0.99:   5.574 ms/op
                 createUser·p0.999:  11.895 ms/op
                 createUser·p0.9999: 12.490 ms/op
                 createUser·p1.00:   12.517 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10559
  mean =      3.024 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 4 
    [ 1.250,  2.500) = 1876 
    [ 2.500,  3.750) = 7444 
    [ 3.750,  5.000) = 1094 
    [ 5.000,  6.250) = 44 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 29 
    [ 8.750, 10.000) = 35 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 31 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.921 ms/op
     p(50.0000) =      2.814 ms/op
     p(90.0000) =      3.891 ms/op
     p(95.0000) =      4.440 ms/op
     p(99.0000) =      5.574 ms/op
     p(99.9000) =     11.895 ms/op
     p(99.9900) =     12.490 ms/op
     p(99.9990) =     12.517 ms/op
     p(99.9999) =     12.517 ms/op
    p(100.0000) =     12.517 ms/op


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
# Warmup Iteration   1: 3.146 ±(99.9%) 0.075 ms/op
Iteration   1: 1.809 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   0.644 ms/op
                 existUser·p0.50:   1.659 ms/op
                 existUser·p0.90:   2.421 ms/op
                 existUser·p0.95:   2.568 ms/op
                 existUser·p0.99:   3.036 ms/op
                 existUser·p0.999:  9.676 ms/op
                 existUser·p0.9999: 10.225 ms/op
                 existUser·p1.00:   10.666 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 17681
  mean =      1.809 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 801 
    [ 1.250,  2.500) = 15595 
    [ 2.500,  3.750) = 1159 
    [ 3.750,  5.000) = 62 
    [ 5.000,  6.250) = 4 
    [ 6.250,  7.500) = 19 
    [ 7.500,  8.750) = 11 
    [ 8.750, 10.000) = 27 
    [10.000, 11.250) = 3 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.644 ms/op
     p(50.0000) =      1.659 ms/op
     p(90.0000) =      2.421 ms/op
     p(95.0000) =      2.568 ms/op
     p(99.0000) =      3.036 ms/op
     p(99.9000) =      9.676 ms/op
     p(99.9900) =     10.225 ms/op
     p(99.9990) =     10.666 ms/op
     p(99.9999) =     10.666 ms/op
    p(100.0000) =     10.666 ms/op


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
# Warmup Iteration   1: 4.349 ±(99.9%) 0.103 ms/op
Iteration   1: 3.289 ±(99.9%) 0.029 ms/op
                 getUser·p0.00:   0.723 ms/op
                 getUser·p0.50:   3.125 ms/op
                 getUser·p0.90:   4.383 ms/op
                 getUser·p0.95:   4.792 ms/op
                 getUser·p0.99:   6.046 ms/op
                 getUser·p0.999:  8.381 ms/op
                 getUser·p0.9999: 8.765 ms/op
                 getUser·p1.00:   8.765 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 9718
  mean =      3.289 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 1 
    [1.000, 1.500) = 30 
    [1.500, 2.000) = 187 
    [2.000, 2.500) = 1078 
    [2.500, 3.000) = 3096 
    [3.000, 3.500) = 1922 
    [3.500, 4.000) = 1654 
    [4.000, 4.500) = 961 
    [4.500, 5.000) = 420 
    [5.000, 5.500) = 135 
    [5.500, 6.000) = 128 
    [6.000, 6.500) = 57 
    [6.500, 7.000) = 3 
    [7.000, 7.500) = 18 
    [7.500, 8.000) = 11 
    [8.000, 8.500) = 16 

  Percentiles, ms/op:
      p(0.0000) =      0.723 ms/op
     p(50.0000) =      3.125 ms/op
     p(90.0000) =      4.383 ms/op
     p(95.0000) =      4.792 ms/op
     p(99.0000) =      6.046 ms/op
     p(99.9000) =      8.381 ms/op
     p(99.9900) =      8.765 ms/op
     p(99.9990) =      8.765 ms/op
     p(99.9999) =      8.765 ms/op
    p(100.0000) =      8.765 ms/op


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
# Warmup Iteration   1: 12.653 ±(99.9%) 0.420 ms/op
Iteration   1: 8.949 ±(99.9%) 0.316 ms/op
                 listUser·p0.00:   1.716 ms/op
                 listUser·p0.50:   8.249 ms/op
                 listUser·p0.90:   11.190 ms/op
                 listUser·p0.95:   12.358 ms/op
                 listUser·p0.99:   18.376 ms/op
                 listUser·p0.999:  68.213 ms/op
                 listUser·p0.9999: 69.861 ms/op
                 listUser·p1.00:   69.861 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3573
  mean =      8.949 ±(99.9%) 0.316 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 93 
    [ 5.000, 10.000) = 2813 
    [10.000, 15.000) = 602 
    [15.000, 20.000) = 33 
    [20.000, 25.000) = 0 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 0 
    [45.000, 50.000) = 0 
    [50.000, 55.000) = 0 
    [55.000, 60.000) = 0 
    [60.000, 65.000) = 17 

  Percentiles, ms/op:
      p(0.0000) =      1.716 ms/op
     p(50.0000) =      8.249 ms/op
     p(90.0000) =     11.190 ms/op
     p(95.0000) =     12.358 ms/op
     p(99.0000) =     18.376 ms/op
     p(99.9000) =     68.213 ms/op
     p(99.9900) =     69.861 ms/op
     p(99.9990) =     69.861 ms/op
     p(99.9999) =     69.861 ms/op
    p(100.0000) =     69.861 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.792          ops/ms
Client.existUser                       thrpt         14.421          ops/ms
Client.getUser                         thrpt          9.978          ops/ms
Client.listUser                        thrpt          2.963          ops/ms
Client.createUser                       avgt          3.230           ms/op
Client.existUser                        avgt          1.907           ms/op
Client.getUser                          avgt          3.278           ms/op
Client.listUser                         avgt          8.150           ms/op
Client.createUser                     sample  10559   3.024 ± 0.029   ms/op
Client.createUser:createUser·p0.00    sample          0.921           ms/op
Client.createUser:createUser·p0.50    sample          2.814           ms/op
Client.createUser:createUser·p0.90    sample          3.891           ms/op
Client.createUser:createUser·p0.95    sample          4.440           ms/op
Client.createUser:createUser·p0.99    sample          5.574           ms/op
Client.createUser:createUser·p0.999   sample         11.895           ms/op
Client.createUser:createUser·p0.9999  sample         12.490           ms/op
Client.createUser:createUser·p1.00    sample         12.517           ms/op
Client.existUser                      sample  17681   1.809 ± 0.015   ms/op
Client.existUser:existUser·p0.00      sample          0.644           ms/op
Client.existUser:existUser·p0.50      sample          1.659           ms/op
Client.existUser:existUser·p0.90      sample          2.421           ms/op
Client.existUser:existUser·p0.95      sample          2.568           ms/op
Client.existUser:existUser·p0.99      sample          3.036           ms/op
Client.existUser:existUser·p0.999     sample          9.676           ms/op
Client.existUser:existUser·p0.9999    sample         10.225           ms/op
Client.existUser:existUser·p1.00      sample         10.666           ms/op
Client.getUser                        sample   9718   3.289 ± 0.029   ms/op
Client.getUser:getUser·p0.00          sample          0.723           ms/op
Client.getUser:getUser·p0.50          sample          3.125           ms/op
Client.getUser:getUser·p0.90          sample          4.383           ms/op
Client.getUser:getUser·p0.95          sample          4.792           ms/op
Client.getUser:getUser·p0.99          sample          6.046           ms/op
Client.getUser:getUser·p0.999         sample          8.381           ms/op
Client.getUser:getUser·p0.9999        sample          8.765           ms/op
Client.getUser:getUser·p1.00          sample          8.765           ms/op
Client.listUser                       sample   3573   8.949 ± 0.316   ms/op
Client.listUser:listUser·p0.00        sample          1.716           ms/op
Client.listUser:listUser·p0.50        sample          8.249           ms/op
Client.listUser:listUser·p0.90        sample         11.190           ms/op
Client.listUser:listUser·p0.95        sample         12.358           ms/op
Client.listUser:listUser·p0.99        sample         18.376           ms/op
Client.listUser:listUser·p0.999       sample         68.213           ms/op
Client.listUser:listUser·p0.9999      sample         69.861           ms/op
Client.listUser:listUser·p1.00        sample         69.861           ms/op
