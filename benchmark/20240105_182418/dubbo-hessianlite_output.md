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
# Warmup Iteration   1: 2.148 ops/ms
Iteration   1: 6.614 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.614 ops/ms


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
# Warmup Iteration   1: 5.855 ops/ms
Iteration   1: 12.728 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  12.728 ops/ms


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
# Warmup Iteration   1: 5.080 ops/ms
Iteration   1: 8.988 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.988 ops/ms


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
# Warmup Iteration   1: 1.934 ops/ms
Iteration   1: 3.072 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.072 ops/ms


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
# Warmup Iteration   1: 5.452 ±(99.9%) 0.069 ms/op
Iteration   1: 3.162 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.162 ms/op


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
# Warmup Iteration   1: 3.420 ±(99.9%) 0.044 ms/op
Iteration   1: 1.931 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.931 ms/op


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
# Warmup Iteration   1: 4.559 ±(99.9%) 0.052 ms/op
Iteration   1: 2.979 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  2.979 ms/op


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
# Warmup Iteration   1: 13.384 ±(99.9%) 0.315 ms/op
Iteration   1: 9.424 ±(99.9%) 0.154 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  9.424 ms/op


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
# Warmup Iteration   1: 5.183 ±(99.9%) 0.129 ms/op
Iteration   1: 3.073 ±(99.9%) 0.052 ms/op
                 createUser·p0.00:   0.641 ms/op
                 createUser·p0.50:   2.806 ms/op
                 createUser·p0.90:   3.686 ms/op
                 createUser·p0.95:   4.588 ms/op
                 createUser·p0.99:   8.594 ms/op
                 createUser·p0.999:  23.468 ms/op
                 createUser·p0.9999: 24.639 ms/op
                 createUser·p1.00:   24.642 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10405
  mean =      3.073 ±(99.9%) 0.052 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2257 
    [ 2.500,  5.000) = 7844 
    [ 5.000,  7.500) = 194 
    [ 7.500, 10.000) = 26 
    [10.000, 12.500) = 20 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 19 
    [17.500, 20.000) = 13 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.641 ms/op
     p(50.0000) =      2.806 ms/op
     p(90.0000) =      3.686 ms/op
     p(95.0000) =      4.588 ms/op
     p(99.0000) =      8.594 ms/op
     p(99.9000) =     23.468 ms/op
     p(99.9900) =     24.639 ms/op
     p(99.9990) =     24.642 ms/op
     p(99.9999) =     24.642 ms/op
    p(100.0000) =     24.642 ms/op


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
# Warmup Iteration   1: 3.037 ±(99.9%) 0.066 ms/op
Iteration   1: 1.785 ±(99.9%) 0.024 ms/op
                 existUser·p0.00:   0.486 ms/op
                 existUser·p0.50:   1.634 ms/op
                 existUser·p0.90:   2.269 ms/op
                 existUser·p0.95:   2.523 ms/op
                 existUser·p0.99:   3.346 ms/op
                 existUser·p0.999:  22.319 ms/op
                 existUser·p0.9999: 23.074 ms/op
                 existUser·p1.00:   23.724 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 17935
  mean =      1.785 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16958 
    [ 2.500,  5.000) = 904 
    [ 5.000,  7.500) = 41 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.486 ms/op
     p(50.0000) =      1.634 ms/op
     p(90.0000) =      2.269 ms/op
     p(95.0000) =      2.523 ms/op
     p(99.0000) =      3.346 ms/op
     p(99.9000) =     22.319 ms/op
     p(99.9900) =     23.074 ms/op
     p(99.9990) =     23.724 ms/op
     p(99.9999) =     23.724 ms/op
    p(100.0000) =     23.724 ms/op


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
# Warmup Iteration   1: 5.082 ±(99.9%) 0.153 ms/op
Iteration   1: 3.178 ±(99.9%) 0.028 ms/op
                 getUser·p0.00:   0.982 ms/op
                 getUser·p0.50:   3.056 ms/op
                 getUser·p0.90:   4.149 ms/op
                 getUser·p0.95:   4.620 ms/op
                 getUser·p0.99:   5.661 ms/op
                 getUser·p0.999:  10.009 ms/op
                 getUser·p0.9999: 11.318 ms/op
                 getUser·p1.00:   11.321 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10080
  mean =      3.178 ±(99.9%) 0.028 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 9 
    [ 1.250,  2.500) = 2109 
    [ 2.500,  3.750) = 6064 
    [ 3.750,  5.000) = 1567 
    [ 5.000,  6.250) = 273 
    [ 6.250,  7.500) = 14 
    [ 7.500,  8.750) = 11 
    [ 8.750, 10.000) = 23 
    [10.000, 11.250) = 9 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.982 ms/op
     p(50.0000) =      3.056 ms/op
     p(90.0000) =      4.149 ms/op
     p(95.0000) =      4.620 ms/op
     p(99.0000) =      5.661 ms/op
     p(99.9000) =     10.009 ms/op
     p(99.9900) =     11.318 ms/op
     p(99.9990) =     11.321 ms/op
     p(99.9999) =     11.321 ms/op
    p(100.0000) =     11.321 ms/op


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
# Warmup Iteration   1: 12.877 ±(99.9%) 0.451 ms/op
Iteration   1: 8.283 ±(99.9%) 0.151 ms/op
                 listUser·p0.00:   2.961 ms/op
                 listUser·p0.50:   7.815 ms/op
                 listUser·p0.90:   10.568 ms/op
                 listUser·p0.95:   12.009 ms/op
                 listUser·p0.99:   19.380 ms/op
                 listUser·p0.999:  34.191 ms/op
                 listUser·p0.9999: 34.931 ms/op
                 listUser·p1.00:   34.931 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3856
  mean =      8.283 ±(99.9%) 0.151 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 86 
    [ 5.000,  7.500) = 1534 
    [ 7.500, 10.000) = 1699 
    [10.000, 12.500) = 381 
    [12.500, 15.000) = 78 
    [15.000, 17.500) = 11 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 9 
    [27.500, 30.000) = 6 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 9 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.961 ms/op
     p(50.0000) =      7.815 ms/op
     p(90.0000) =     10.568 ms/op
     p(95.0000) =     12.009 ms/op
     p(99.0000) =     19.380 ms/op
     p(99.9000) =     34.191 ms/op
     p(99.9900) =     34.931 ms/op
     p(99.9990) =     34.931 ms/op
     p(99.9999) =     34.931 ms/op
    p(100.0000) =     34.931 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.614          ops/ms
Client.existUser                       thrpt         12.728          ops/ms
Client.getUser                         thrpt          8.988          ops/ms
Client.listUser                        thrpt          3.072          ops/ms
Client.createUser                       avgt          3.162           ms/op
Client.existUser                        avgt          1.931           ms/op
Client.getUser                          avgt          2.979           ms/op
Client.listUser                         avgt          9.424           ms/op
Client.createUser                     sample  10405   3.073 ± 0.052   ms/op
Client.createUser:createUser·p0.00    sample          0.641           ms/op
Client.createUser:createUser·p0.50    sample          2.806           ms/op
Client.createUser:createUser·p0.90    sample          3.686           ms/op
Client.createUser:createUser·p0.95    sample          4.588           ms/op
Client.createUser:createUser·p0.99    sample          8.594           ms/op
Client.createUser:createUser·p0.999   sample         23.468           ms/op
Client.createUser:createUser·p0.9999  sample         24.639           ms/op
Client.createUser:createUser·p1.00    sample         24.642           ms/op
Client.existUser                      sample  17935   1.785 ± 0.024   ms/op
Client.existUser:existUser·p0.00      sample          0.486           ms/op
Client.existUser:existUser·p0.50      sample          1.634           ms/op
Client.existUser:existUser·p0.90      sample          2.269           ms/op
Client.existUser:existUser·p0.95      sample          2.523           ms/op
Client.existUser:existUser·p0.99      sample          3.346           ms/op
Client.existUser:existUser·p0.999     sample         22.319           ms/op
Client.existUser:existUser·p0.9999    sample         23.074           ms/op
Client.existUser:existUser·p1.00      sample         23.724           ms/op
Client.getUser                        sample  10080   3.178 ± 0.028   ms/op
Client.getUser:getUser·p0.00          sample          0.982           ms/op
Client.getUser:getUser·p0.50          sample          3.056           ms/op
Client.getUser:getUser·p0.90          sample          4.149           ms/op
Client.getUser:getUser·p0.95          sample          4.620           ms/op
Client.getUser:getUser·p0.99          sample          5.661           ms/op
Client.getUser:getUser·p0.999         sample         10.009           ms/op
Client.getUser:getUser·p0.9999        sample         11.318           ms/op
Client.getUser:getUser·p1.00          sample         11.321           ms/op
Client.listUser                       sample   3856   8.283 ± 0.151   ms/op
Client.listUser:listUser·p0.00        sample          2.961           ms/op
Client.listUser:listUser·p0.50        sample          7.815           ms/op
Client.listUser:listUser·p0.90        sample         10.568           ms/op
Client.listUser:listUser·p0.95        sample         12.009           ms/op
Client.listUser:listUser·p0.99        sample         19.380           ms/op
Client.listUser:listUser·p0.999       sample         34.191           ms/op
Client.listUser:listUser·p0.9999      sample         34.931           ms/op
Client.listUser:listUser·p1.00        sample         34.931           ms/op
