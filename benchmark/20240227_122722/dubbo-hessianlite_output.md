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
# Warmup Iteration   1: 2.341 ops/ms
Iteration   1: 5.931 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.931 ops/ms


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
# Warmup Iteration   1: 5.448 ops/ms
Iteration   1: 11.650 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  11.650 ops/ms


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
# Warmup Iteration   1: 3.600 ops/ms
Iteration   1: 9.103 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  9.103 ops/ms


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
# Warmup Iteration   1: 2.129 ops/ms
Iteration   1: 3.681 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.681 ops/ms


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
# Warmup Iteration   1: 5.396 ±(99.9%) 0.120 ms/op
Iteration   1: 3.245 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.245 ms/op


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
# Warmup Iteration   1: 2.960 ±(99.9%) 0.033 ms/op
Iteration   1: 1.810 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.810 ms/op


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
# Warmup Iteration   1: 5.292 ±(99.9%) 0.048 ms/op
Iteration   1: 3.318 ±(99.9%) 0.023 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.318 ms/op


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
# Warmup Iteration   1: 12.925 ±(99.9%) 0.214 ms/op
Iteration   1: 8.753 ±(99.9%) 0.085 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.753 ms/op


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
# Warmup Iteration   1: 4.937 ±(99.9%) 0.102 ms/op
Iteration   1: 3.041 ±(99.9%) 0.033 ms/op
                 createUser·p0.00:   0.922 ms/op
                 createUser·p0.50:   2.765 ms/op
                 createUser·p0.90:   3.670 ms/op
                 createUser·p0.95:   4.809 ms/op
                 createUser·p0.99:   7.815 ms/op
                 createUser·p0.999:  11.305 ms/op
                 createUser·p0.9999: 11.386 ms/op
                 createUser·p1.00:   11.387 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10519
  mean =      3.041 ±(99.9%) 0.033 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 23 
    [ 1.250,  2.500) = 1668 
    [ 2.500,  3.750) = 7900 
    [ 3.750,  5.000) = 438 
    [ 5.000,  6.250) = 198 
    [ 6.250,  7.500) = 112 
    [ 7.500,  8.750) = 139 
    [ 8.750, 10.000) = 27 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 14 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.922 ms/op
     p(50.0000) =      2.765 ms/op
     p(90.0000) =      3.670 ms/op
     p(95.0000) =      4.809 ms/op
     p(99.0000) =      7.815 ms/op
     p(99.9000) =     11.305 ms/op
     p(99.9900) =     11.386 ms/op
     p(99.9990) =     11.387 ms/op
     p(99.9999) =     11.387 ms/op
    p(100.0000) =     11.387 ms/op


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
# Warmup Iteration   1: 3.068 ±(99.9%) 0.069 ms/op
Iteration   1: 1.808 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.641 ms/op
                 existUser·p0.50:   1.741 ms/op
                 existUser·p0.90:   2.146 ms/op
                 existUser·p0.95:   2.359 ms/op
                 existUser·p0.99:   2.908 ms/op
                 existUser·p0.999:  10.486 ms/op
                 existUser·p0.9999: 10.617 ms/op
                 existUser·p1.00:   10.617 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 17677
  mean =      1.808 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  1.000) = 40 
    [ 1.000,  2.000) = 14636 
    [ 2.000,  3.000) = 2851 
    [ 3.000,  4.000) = 67 
    [ 4.000,  5.000) = 38 
    [ 5.000,  6.000) = 1 
    [ 6.000,  7.000) = 12 
    [ 7.000,  8.000) = 0 
    [ 8.000,  9.000) = 0 
    [ 9.000, 10.000) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.641 ms/op
     p(50.0000) =      1.741 ms/op
     p(90.0000) =      2.146 ms/op
     p(95.0000) =      2.359 ms/op
     p(99.0000) =      2.908 ms/op
     p(99.9000) =     10.486 ms/op
     p(99.9900) =     10.617 ms/op
     p(99.9990) =     10.617 ms/op
     p(99.9999) =     10.617 ms/op
    p(100.0000) =     10.617 ms/op


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
# Warmup Iteration   1: 4.531 ±(99.9%) 0.113 ms/op
Iteration   1: 2.907 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   0.926 ms/op
                 getUser·p0.50:   2.826 ms/op
                 getUser·p0.90:   3.590 ms/op
                 getUser·p0.95:   3.891 ms/op
                 getUser·p0.99:   5.161 ms/op
                 getUser·p0.999:  6.166 ms/op
                 getUser·p0.9999: 8.997 ms/op
                 getUser·p1.00:   9.191 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 11165
  mean =      2.907 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.000) = 2 
    [ 1.000,  2.000) = 420 
    [ 2.000,  3.000) = 6440 
    [ 3.000,  4.000) = 3838 
    [ 4.000,  5.000) = 322 
    [ 5.000,  6.000) = 127 
    [ 6.000,  7.000) = 14 
    [ 7.000,  8.000) = 1 
    [ 8.000,  9.000) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.926 ms/op
     p(50.0000) =      2.826 ms/op
     p(90.0000) =      3.590 ms/op
     p(95.0000) =      3.891 ms/op
     p(99.0000) =      5.161 ms/op
     p(99.9000) =      6.166 ms/op
     p(99.9900) =      8.997 ms/op
     p(99.9990) =      9.191 ms/op
     p(99.9999) =      9.191 ms/op
    p(100.0000) =      9.191 ms/op


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
# Warmup Iteration   1: 12.903 ±(99.9%) 0.441 ms/op
Iteration   1: 7.998 ±(99.9%) 0.116 ms/op
                 listUser·p0.00:   2.400 ms/op
                 listUser·p0.50:   7.799 ms/op
                 listUser·p0.90:   10.486 ms/op
                 listUser·p0.95:   11.993 ms/op
                 listUser·p0.99:   14.631 ms/op
                 listUser·p0.999:  25.258 ms/op
                 listUser·p0.9999: 40.174 ms/op
                 listUser·p1.00:   40.174 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 4099
  mean =      7.998 ±(99.9%) 0.116 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 210 
    [ 5.000, 10.000) = 3366 
    [10.000, 15.000) = 492 
    [15.000, 20.000) = 26 
    [20.000, 25.000) = 1 
    [25.000, 30.000) = 1 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 2 
    [40.000, 45.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      2.400 ms/op
     p(50.0000) =      7.799 ms/op
     p(90.0000) =     10.486 ms/op
     p(95.0000) =     11.993 ms/op
     p(99.0000) =     14.631 ms/op
     p(99.9000) =     25.258 ms/op
     p(99.9900) =     40.174 ms/op
     p(99.9990) =     40.174 ms/op
     p(99.9999) =     40.174 ms/op
    p(100.0000) =     40.174 ms/op


# Run complete. Total time: 00:01:22

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.931          ops/ms
Client.existUser                       thrpt         11.650          ops/ms
Client.getUser                         thrpt          9.103          ops/ms
Client.listUser                        thrpt          3.681          ops/ms
Client.createUser                       avgt          3.245           ms/op
Client.existUser                        avgt          1.810           ms/op
Client.getUser                          avgt          3.318           ms/op
Client.listUser                         avgt          8.753           ms/op
Client.createUser                     sample  10519   3.041 ± 0.033   ms/op
Client.createUser:createUser·p0.00    sample          0.922           ms/op
Client.createUser:createUser·p0.50    sample          2.765           ms/op
Client.createUser:createUser·p0.90    sample          3.670           ms/op
Client.createUser:createUser·p0.95    sample          4.809           ms/op
Client.createUser:createUser·p0.99    sample          7.815           ms/op
Client.createUser:createUser·p0.999   sample         11.305           ms/op
Client.createUser:createUser·p0.9999  sample         11.386           ms/op
Client.createUser:createUser·p1.00    sample         11.387           ms/op
Client.existUser                      sample  17677   1.808 ± 0.012   ms/op
Client.existUser:existUser·p0.00      sample          0.641           ms/op
Client.existUser:existUser·p0.50      sample          1.741           ms/op
Client.existUser:existUser·p0.90      sample          2.146           ms/op
Client.existUser:existUser·p0.95      sample          2.359           ms/op
Client.existUser:existUser·p0.99      sample          2.908           ms/op
Client.existUser:existUser·p0.999     sample         10.486           ms/op
Client.existUser:existUser·p0.9999    sample         10.617           ms/op
Client.existUser:existUser·p1.00      sample         10.617           ms/op
Client.getUser                        sample  11165   2.907 ± 0.019   ms/op
Client.getUser:getUser·p0.00          sample          0.926           ms/op
Client.getUser:getUser·p0.50          sample          2.826           ms/op
Client.getUser:getUser·p0.90          sample          3.590           ms/op
Client.getUser:getUser·p0.95          sample          3.891           ms/op
Client.getUser:getUser·p0.99          sample          5.161           ms/op
Client.getUser:getUser·p0.999         sample          6.166           ms/op
Client.getUser:getUser·p0.9999        sample          8.997           ms/op
Client.getUser:getUser·p1.00          sample          9.191           ms/op
Client.listUser                       sample   4099   7.998 ± 0.116   ms/op
Client.listUser:listUser·p0.00        sample          2.400           ms/op
Client.listUser:listUser·p0.50        sample          7.799           ms/op
Client.listUser:listUser·p0.90        sample         10.486           ms/op
Client.listUser:listUser·p0.95        sample         11.993           ms/op
Client.listUser:listUser·p0.99        sample         14.631           ms/op
Client.listUser:listUser·p0.999       sample         25.258           ms/op
Client.listUser:listUser·p0.9999      sample         40.174           ms/op
Client.listUser:listUser·p1.00        sample         40.174           ms/op
