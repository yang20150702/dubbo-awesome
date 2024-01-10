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
# Warmup Iteration   1: 2.354 ops/ms
Iteration   1: 6.428 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.428 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:16
# Fork: 1 of 1
# Warmup Iteration   1: 5.802 ops/ms
Iteration   1: 10.858 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  10.858 ops/ms


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
# Warmup Iteration   1: 4.662 ops/ms
Iteration   1: 9.030 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  9.030 ops/ms


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
# Warmup Iteration   1: 1.996 ops/ms
Iteration   1: 3.463 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.463 ops/ms


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
# Warmup Iteration   1: 5.760 ±(99.9%) 0.092 ms/op
Iteration   1: 2.931 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.931 ms/op


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
# Warmup Iteration   1: 3.142 ±(99.9%) 0.033 ms/op
Iteration   1: 1.882 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.882 ms/op


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
# Warmup Iteration   1: 5.039 ±(99.9%) 0.064 ms/op
Iteration   1: 3.105 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.105 ms/op


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
# Warmup Iteration   1: 13.134 ±(99.9%) 0.257 ms/op
Iteration   1: 8.681 ±(99.9%) 0.086 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.681 ms/op


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
# Warmup Iteration   1: 5.088 ±(99.9%) 0.106 ms/op
Iteration   1: 3.269 ±(99.9%) 0.041 ms/op
                 createUser·p0.00:   0.670 ms/op
                 createUser·p0.50:   2.908 ms/op
                 createUser·p0.90:   5.102 ms/op
                 createUser·p0.95:   5.803 ms/op
                 createUser·p0.99:   7.855 ms/op
                 createUser·p0.999:  12.060 ms/op
                 createUser·p0.9999: 12.993 ms/op
                 createUser·p1.00:   12.993 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 9912
  mean =      3.269 ±(99.9%) 0.041 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 19 
    [ 1.250,  2.500) = 1983 
    [ 2.500,  3.750) = 6049 
    [ 3.750,  5.000) = 860 
    [ 5.000,  6.250) = 694 
    [ 6.250,  7.500) = 200 
    [ 7.500,  8.750) = 31 
    [ 8.750, 10.000) = 33 
    [10.000, 11.250) = 25 
    [11.250, 12.500) = 14 
    [12.500, 13.750) = 4 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.670 ms/op
     p(50.0000) =      2.908 ms/op
     p(90.0000) =      5.102 ms/op
     p(95.0000) =      5.803 ms/op
     p(99.0000) =      7.855 ms/op
     p(99.9000) =     12.060 ms/op
     p(99.9900) =     12.993 ms/op
     p(99.9990) =     12.993 ms/op
     p(99.9999) =     12.993 ms/op
    p(100.0000) =     12.993 ms/op


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
# Warmup Iteration   1: 2.966 ±(99.9%) 0.068 ms/op
Iteration   1: 1.787 ±(99.9%) 0.024 ms/op
                 existUser·p0.00:   0.668 ms/op
                 existUser·p0.50:   1.634 ms/op
                 existUser·p0.90:   2.298 ms/op
                 existUser·p0.95:   2.540 ms/op
                 existUser·p0.99:   3.213 ms/op
                 existUser·p0.999:  22.774 ms/op
                 existUser·p0.9999: 22.879 ms/op
                 existUser·p1.00:   22.905 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 17956
  mean =      1.787 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16901 
    [ 2.500,  5.000) = 1005 
    [ 5.000,  7.500) = 18 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.668 ms/op
     p(50.0000) =      1.634 ms/op
     p(90.0000) =      2.298 ms/op
     p(95.0000) =      2.540 ms/op
     p(99.0000) =      3.213 ms/op
     p(99.9000) =     22.774 ms/op
     p(99.9900) =     22.879 ms/op
     p(99.9990) =     22.905 ms/op
     p(99.9999) =     22.905 ms/op
    p(100.0000) =     22.905 ms/op


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
# Warmup Iteration   1: 4.235 ±(99.9%) 0.093 ms/op
Iteration   1: 3.261 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   1.029 ms/op
                 getUser·p0.50:   3.154 ms/op
                 getUser·p0.90:   4.149 ms/op
                 getUser·p0.95:   4.481 ms/op
                 getUser·p0.99:   5.612 ms/op
                 getUser·p0.999:  7.303 ms/op
                 getUser·p0.9999: 8.364 ms/op
                 getUser·p1.00:   8.364 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 9850
  mean =      3.261 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [1.000, 1.500) = 19 
    [1.500, 2.000) = 90 
    [2.000, 2.500) = 752 
    [2.500, 3.000) = 3281 
    [3.000, 3.500) = 2611 
    [3.500, 4.000) = 1744 
    [4.000, 4.500) = 870 
    [4.500, 5.000) = 270 
    [5.000, 5.500) = 73 
    [5.500, 6.000) = 75 
    [6.000, 6.500) = 20 
    [6.500, 7.000) = 4 
    [7.000, 7.500) = 37 
    [7.500, 8.000) = 2 
    [8.000, 8.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.029 ms/op
     p(50.0000) =      3.154 ms/op
     p(90.0000) =      4.149 ms/op
     p(95.0000) =      4.481 ms/op
     p(99.0000) =      5.612 ms/op
     p(99.9000) =      7.303 ms/op
     p(99.9900) =      8.364 ms/op
     p(99.9990) =      8.364 ms/op
     p(99.9999) =      8.364 ms/op
    p(100.0000) =      8.364 ms/op


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
# Warmup Iteration   1: 12.315 ±(99.9%) 0.369 ms/op
Iteration   1: 8.243 ±(99.9%) 0.124 ms/op
                 listUser·p0.00:   3.142 ms/op
                 listUser·p0.50:   7.815 ms/op
                 listUser·p0.90:   11.158 ms/op
                 listUser·p0.95:   12.724 ms/op
                 listUser·p0.99:   17.961 ms/op
                 listUser·p0.999:  20.192 ms/op
                 listUser·p0.9999: 21.529 ms/op
                 listUser·p1.00:   21.529 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3887
  mean =      8.243 ±(99.9%) 0.124 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 104 
    [ 5.000,  7.500) = 1572 
    [ 7.500, 10.000) = 1572 
    [10.000, 12.500) = 421 
    [12.500, 15.000) = 137 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 45 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      3.142 ms/op
     p(50.0000) =      7.815 ms/op
     p(90.0000) =     11.158 ms/op
     p(95.0000) =     12.724 ms/op
     p(99.0000) =     17.961 ms/op
     p(99.9000) =     20.192 ms/op
     p(99.9900) =     21.529 ms/op
     p(99.9990) =     21.529 ms/op
     p(99.9999) =     21.529 ms/op
    p(100.0000) =     21.529 ms/op


# Run complete. Total time: 00:01:22

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.428          ops/ms
Client.existUser                       thrpt         10.858          ops/ms
Client.getUser                         thrpt          9.030          ops/ms
Client.listUser                        thrpt          3.463          ops/ms
Client.createUser                       avgt          2.931           ms/op
Client.existUser                        avgt          1.882           ms/op
Client.getUser                          avgt          3.105           ms/op
Client.listUser                         avgt          8.681           ms/op
Client.createUser                     sample   9912   3.269 ± 0.041   ms/op
Client.createUser:createUser·p0.00    sample          0.670           ms/op
Client.createUser:createUser·p0.50    sample          2.908           ms/op
Client.createUser:createUser·p0.90    sample          5.102           ms/op
Client.createUser:createUser·p0.95    sample          5.803           ms/op
Client.createUser:createUser·p0.99    sample          7.855           ms/op
Client.createUser:createUser·p0.999   sample         12.060           ms/op
Client.createUser:createUser·p0.9999  sample         12.993           ms/op
Client.createUser:createUser·p1.00    sample         12.993           ms/op
Client.existUser                      sample  17956   1.787 ± 0.024   ms/op
Client.existUser:existUser·p0.00      sample          0.668           ms/op
Client.existUser:existUser·p0.50      sample          1.634           ms/op
Client.existUser:existUser·p0.90      sample          2.298           ms/op
Client.existUser:existUser·p0.95      sample          2.540           ms/op
Client.existUser:existUser·p0.99      sample          3.213           ms/op
Client.existUser:existUser·p0.999     sample         22.774           ms/op
Client.existUser:existUser·p0.9999    sample         22.879           ms/op
Client.existUser:existUser·p1.00      sample         22.905           ms/op
Client.getUser                        sample   9850   3.261 ± 0.024   ms/op
Client.getUser:getUser·p0.00          sample          1.029           ms/op
Client.getUser:getUser·p0.50          sample          3.154           ms/op
Client.getUser:getUser·p0.90          sample          4.149           ms/op
Client.getUser:getUser·p0.95          sample          4.481           ms/op
Client.getUser:getUser·p0.99          sample          5.612           ms/op
Client.getUser:getUser·p0.999         sample          7.303           ms/op
Client.getUser:getUser·p0.9999        sample          8.364           ms/op
Client.getUser:getUser·p1.00          sample          8.364           ms/op
Client.listUser                       sample   3887   8.243 ± 0.124   ms/op
Client.listUser:listUser·p0.00        sample          3.142           ms/op
Client.listUser:listUser·p0.50        sample          7.815           ms/op
Client.listUser:listUser·p0.90        sample         11.158           ms/op
Client.listUser:listUser·p0.95        sample         12.724           ms/op
Client.listUser:listUser·p0.99        sample         17.961           ms/op
Client.listUser:listUser·p0.999       sample         20.192           ms/op
Client.listUser:listUser·p0.9999      sample         21.529           ms/op
Client.listUser:listUser·p1.00        sample         21.529           ms/op
