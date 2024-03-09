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
# Warmup Iteration   1: 2.237 ops/ms
Iteration   1: 5.578 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.578 ops/ms


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
# Warmup Iteration   1: 6.237 ops/ms
Iteration   1: 13.213 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  13.213 ops/ms


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
# Warmup Iteration   1: 4.420 ops/ms
Iteration   1: 9.533 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  9.533 ops/ms


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
# Warmup Iteration   1: 2.144 ops/ms
Iteration   1: 3.333 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.333 ops/ms


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
# Warmup Iteration   1: 5.931 ±(99.9%) 0.101 ms/op
Iteration   1: 3.112 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.112 ms/op


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
# Warmup Iteration   1: 3.145 ±(99.9%) 0.034 ms/op
Iteration   1: 1.841 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.841 ms/op


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
# Warmup Iteration   1: 4.634 ±(99.9%) 0.073 ms/op
Iteration   1: 2.824 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  2.824 ms/op


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
# Warmup Iteration   1: 12.058 ±(99.9%) 0.212 ms/op
Iteration   1: 9.350 ±(99.9%) 0.098 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  9.350 ms/op


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
# Warmup Iteration   1: 5.239 ±(99.9%) 0.133 ms/op
Iteration   1: 3.181 ±(99.9%) 0.029 ms/op
                 createUser·p0.00:   1.475 ms/op
                 createUser·p0.50:   3.121 ms/op
                 createUser·p0.90:   3.809 ms/op
                 createUser·p0.95:   4.071 ms/op
                 createUser·p0.99:   5.792 ms/op
                 createUser·p0.999:  14.778 ms/op
                 createUser·p0.9999: 14.909 ms/op
                 createUser·p1.00:   14.909 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10202
  mean =      3.181 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 1143 
    [ 2.500,  3.750) = 7891 
    [ 3.750,  5.000) = 1013 
    [ 5.000,  6.250) = 81 
    [ 6.250,  7.500) = 14 
    [ 7.500,  8.750) = 28 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.475 ms/op
     p(50.0000) =      3.121 ms/op
     p(90.0000) =      3.809 ms/op
     p(95.0000) =      4.071 ms/op
     p(99.0000) =      5.792 ms/op
     p(99.9000) =     14.778 ms/op
     p(99.9900) =     14.909 ms/op
     p(99.9990) =     14.909 ms/op
     p(99.9999) =     14.909 ms/op
    p(100.0000) =     14.909 ms/op


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
# Warmup Iteration   1: 2.880 ±(99.9%) 0.082 ms/op
Iteration   1: 1.629 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.546 ms/op
                 existUser·p0.50:   1.532 ms/op
                 existUser·p0.90:   2.095 ms/op
                 existUser·p0.95:   2.376 ms/op
                 existUser·p0.99:   3.263 ms/op
                 existUser·p0.999:  4.149 ms/op
                 existUser·p0.9999: 4.998 ms/op
                 existUser·p1.00:   5.325 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 19734
  mean =      1.629 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 136 
    [1.000, 1.500) = 8558 
    [1.500, 2.000) = 8519 
    [2.000, 2.500) = 1752 
    [2.500, 3.000) = 472 
    [3.000, 3.500) = 150 
    [3.500, 4.000) = 97 
    [4.000, 4.500) = 40 
    [4.500, 5.000) = 9 
    [5.000, 5.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.546 ms/op
     p(50.0000) =      1.532 ms/op
     p(90.0000) =      2.095 ms/op
     p(95.0000) =      2.376 ms/op
     p(99.0000) =      3.263 ms/op
     p(99.9000) =      4.149 ms/op
     p(99.9900) =      4.998 ms/op
     p(99.9990) =      5.325 ms/op
     p(99.9999) =      5.325 ms/op
    p(100.0000) =      5.325 ms/op


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
# Warmup Iteration   1: 4.587 ±(99.9%) 0.106 ms/op
Iteration   1: 2.910 ±(99.9%) 0.041 ms/op
                 getUser·p0.00:   0.741 ms/op
                 getUser·p0.50:   2.826 ms/op
                 getUser·p0.90:   3.552 ms/op
                 getUser·p0.95:   3.914 ms/op
                 getUser·p0.99:   5.308 ms/op
                 getUser·p0.999:  23.921 ms/op
                 getUser·p0.9999: 24.999 ms/op
                 getUser·p1.00:   25.002 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10986
  mean =      2.910 ±(99.9%) 0.041 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3260 
    [ 2.500,  5.000) = 7585 
    [ 5.000,  7.500) = 103 
    [ 7.500, 10.000) = 6 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.741 ms/op
     p(50.0000) =      2.826 ms/op
     p(90.0000) =      3.552 ms/op
     p(95.0000) =      3.914 ms/op
     p(99.0000) =      5.308 ms/op
     p(99.9000) =     23.921 ms/op
     p(99.9900) =     24.999 ms/op
     p(99.9990) =     25.002 ms/op
     p(99.9999) =     25.002 ms/op
    p(100.0000) =     25.002 ms/op


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
# Warmup Iteration   1: 13.327 ±(99.9%) 0.507 ms/op
Iteration   1: 7.734 ±(99.9%) 0.102 ms/op
                 listUser·p0.00:   2.757 ms/op
                 listUser·p0.50:   7.447 ms/op
                 listUser·p0.90:   10.338 ms/op
                 listUser·p0.95:   11.239 ms/op
                 listUser·p0.99:   14.570 ms/op
                 listUser·p0.999:  18.149 ms/op
                 listUser·p0.9999: 20.316 ms/op
                 listUser·p1.00:   20.316 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 4135
  mean =      7.734 ±(99.9%) 0.102 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 221 
    [ 5.000,  7.500) = 1901 
    [ 7.500, 10.000) = 1520 
    [10.000, 12.500) = 412 
    [12.500, 15.000) = 44 
    [15.000, 17.500) = 30 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.757 ms/op
     p(50.0000) =      7.447 ms/op
     p(90.0000) =     10.338 ms/op
     p(95.0000) =     11.239 ms/op
     p(99.0000) =     14.570 ms/op
     p(99.9000) =     18.149 ms/op
     p(99.9900) =     20.316 ms/op
     p(99.9990) =     20.316 ms/op
     p(99.9999) =     20.316 ms/op
    p(100.0000) =     20.316 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.578          ops/ms
Client.existUser                       thrpt         13.213          ops/ms
Client.getUser                         thrpt          9.533          ops/ms
Client.listUser                        thrpt          3.333          ops/ms
Client.createUser                       avgt          3.112           ms/op
Client.existUser                        avgt          1.841           ms/op
Client.getUser                          avgt          2.824           ms/op
Client.listUser                         avgt          9.350           ms/op
Client.createUser                     sample  10202   3.181 ± 0.029   ms/op
Client.createUser:createUser·p0.00    sample          1.475           ms/op
Client.createUser:createUser·p0.50    sample          3.121           ms/op
Client.createUser:createUser·p0.90    sample          3.809           ms/op
Client.createUser:createUser·p0.95    sample          4.071           ms/op
Client.createUser:createUser·p0.99    sample          5.792           ms/op
Client.createUser:createUser·p0.999   sample         14.778           ms/op
Client.createUser:createUser·p0.9999  sample         14.909           ms/op
Client.createUser:createUser·p1.00    sample         14.909           ms/op
Client.existUser                      sample  19734   1.629 ± 0.010   ms/op
Client.existUser:existUser·p0.00      sample          0.546           ms/op
Client.existUser:existUser·p0.50      sample          1.532           ms/op
Client.existUser:existUser·p0.90      sample          2.095           ms/op
Client.existUser:existUser·p0.95      sample          2.376           ms/op
Client.existUser:existUser·p0.99      sample          3.263           ms/op
Client.existUser:existUser·p0.999     sample          4.149           ms/op
Client.existUser:existUser·p0.9999    sample          4.998           ms/op
Client.existUser:existUser·p1.00      sample          5.325           ms/op
Client.getUser                        sample  10986   2.910 ± 0.041   ms/op
Client.getUser:getUser·p0.00          sample          0.741           ms/op
Client.getUser:getUser·p0.50          sample          2.826           ms/op
Client.getUser:getUser·p0.90          sample          3.552           ms/op
Client.getUser:getUser·p0.95          sample          3.914           ms/op
Client.getUser:getUser·p0.99          sample          5.308           ms/op
Client.getUser:getUser·p0.999         sample         23.921           ms/op
Client.getUser:getUser·p0.9999        sample         24.999           ms/op
Client.getUser:getUser·p1.00          sample         25.002           ms/op
Client.listUser                       sample   4135   7.734 ± 0.102   ms/op
Client.listUser:listUser·p0.00        sample          2.757           ms/op
Client.listUser:listUser·p0.50        sample          7.447           ms/op
Client.listUser:listUser·p0.90        sample         10.338           ms/op
Client.listUser:listUser·p0.95        sample         11.239           ms/op
Client.listUser:listUser·p0.99        sample         14.570           ms/op
Client.listUser:listUser·p0.999       sample         18.149           ms/op
Client.listUser:listUser·p0.9999      sample         20.316           ms/op
Client.listUser:listUser·p1.00        sample         20.316           ms/op
