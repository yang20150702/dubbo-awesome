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
# Warmup Iteration   1: 2.298 ops/ms
Iteration   1: 6.411 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.411 ops/ms


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
# Warmup Iteration   1: 6.177 ops/ms
Iteration   1: 13.496 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  13.496 ops/ms


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
# Warmup Iteration   1: 3.751 ops/ms
Iteration   1: 8.108 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.108 ops/ms


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
# Warmup Iteration   1: 1.887 ops/ms
Iteration   1: 4.129 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  4.129 ops/ms


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
# Warmup Iteration   1: 5.293 ±(99.9%) 0.094 ms/op
Iteration   1: 2.867 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.867 ms/op


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
# Warmup Iteration   1: 3.337 ±(99.9%) 0.045 ms/op
Iteration   1: 1.969 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.969 ms/op


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
# Warmup Iteration   1: 4.622 ±(99.9%) 0.059 ms/op
Iteration   1: 3.157 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.157 ms/op


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
# Warmup Iteration   1: 11.675 ±(99.9%) 0.199 ms/op
Iteration   1: 8.011 ±(99.9%) 0.068 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.011 ms/op


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
# Warmup Iteration   1: 4.927 ±(99.9%) 0.124 ms/op
Iteration   1: 2.913 ±(99.9%) 0.043 ms/op
                 createUser·p0.00:   1.122 ms/op
                 createUser·p0.50:   2.699 ms/op
                 createUser·p0.90:   3.690 ms/op
                 createUser·p0.95:   4.202 ms/op
                 createUser·p0.99:   11.129 ms/op
                 createUser·p0.999:  16.532 ms/op
                 createUser·p0.9999: 16.646 ms/op
                 createUser·p1.00:   16.646 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10985
  mean =      2.913 ±(99.9%) 0.043 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2 
    [ 1.250,  2.500) = 4196 
    [ 2.500,  3.750) = 5797 
    [ 3.750,  5.000) = 733 
    [ 5.000,  6.250) = 80 
    [ 6.250,  7.500) = 17 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 21 
    [10.000, 11.250) = 36 
    [11.250, 12.500) = 40 
    [12.500, 13.750) = 29 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 8 
    [16.250, 17.500) = 24 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.122 ms/op
     p(50.0000) =      2.699 ms/op
     p(90.0000) =      3.690 ms/op
     p(95.0000) =      4.202 ms/op
     p(99.0000) =     11.129 ms/op
     p(99.9000) =     16.532 ms/op
     p(99.9900) =     16.646 ms/op
     p(99.9990) =     16.646 ms/op
     p(99.9999) =     16.646 ms/op
    p(100.0000) =     16.646 ms/op


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
# Warmup Iteration   1: 3.196 ±(99.9%) 0.080 ms/op
Iteration   1: 1.837 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.565 ms/op
                 existUser·p0.50:   1.815 ms/op
                 existUser·p0.90:   2.286 ms/op
                 existUser·p0.95:   2.474 ms/op
                 existUser·p0.99:   3.266 ms/op
                 existUser·p0.999:  4.932 ms/op
                 existUser·p0.9999: 5.163 ms/op
                 existUser·p1.00:   5.169 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 17434
  mean =      1.837 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 117 
    [1.000, 1.500) = 3017 
    [1.500, 2.000) = 9545 
    [2.000, 2.500) = 3966 
    [2.500, 3.000) = 531 
    [3.000, 3.500) = 140 
    [3.500, 4.000) = 49 
    [4.000, 4.500) = 17 
    [4.500, 5.000) = 41 
    [5.000, 5.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      0.565 ms/op
     p(50.0000) =      1.815 ms/op
     p(90.0000) =      2.286 ms/op
     p(95.0000) =      2.474 ms/op
     p(99.0000) =      3.266 ms/op
     p(99.9000) =      4.932 ms/op
     p(99.9900) =      5.163 ms/op
     p(99.9990) =      5.169 ms/op
     p(99.9999) =      5.169 ms/op
    p(100.0000) =      5.169 ms/op


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
# Warmup Iteration   1: 4.445 ±(99.9%) 0.100 ms/op
Iteration   1: 2.863 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   0.614 ms/op
                 getUser·p0.50:   2.781 ms/op
                 getUser·p0.90:   3.609 ms/op
                 getUser·p0.95:   3.912 ms/op
                 getUser·p0.99:   4.940 ms/op
                 getUser·p0.999:  6.455 ms/op
                 getUser·p0.9999: 8.525 ms/op
                 getUser·p1.00:   8.651 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 11208
  mean =      2.863 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 1 
    [1.000, 1.500) = 19 
    [1.500, 2.000) = 237 
    [2.000, 2.500) = 3818 
    [2.500, 3.000) = 2721 
    [3.000, 3.500) = 2827 
    [3.500, 4.000) = 1147 
    [4.000, 4.500) = 252 
    [4.500, 5.000) = 91 
    [5.000, 5.500) = 28 
    [5.500, 6.000) = 24 
    [6.000, 6.500) = 34 
    [6.500, 7.000) = 2 
    [7.000, 7.500) = 4 
    [7.500, 8.000) = 2 
    [8.000, 8.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.614 ms/op
     p(50.0000) =      2.781 ms/op
     p(90.0000) =      3.609 ms/op
     p(95.0000) =      3.912 ms/op
     p(99.0000) =      4.940 ms/op
     p(99.9000) =      6.455 ms/op
     p(99.9900) =      8.525 ms/op
     p(99.9990) =      8.651 ms/op
     p(99.9999) =      8.651 ms/op
    p(100.0000) =      8.651 ms/op


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
# Warmup Iteration   1: 11.978 ±(99.9%) 0.372 ms/op
Iteration   1: 8.618 ±(99.9%) 0.128 ms/op
                 listUser·p0.00:   3.138 ms/op
                 listUser·p0.50:   8.298 ms/op
                 listUser·p0.90:   11.221 ms/op
                 listUser·p0.95:   12.304 ms/op
                 listUser·p0.99:   18.282 ms/op
                 listUser·p0.999:  23.373 ms/op
                 listUser·p0.9999: 24.150 ms/op
                 listUser·p1.00:   24.150 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3700
  mean =      8.618 ±(99.9%) 0.128 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 70 
    [ 5.000,  7.500) = 1145 
    [ 7.500, 10.000) = 1668 
    [10.000, 12.500) = 661 
    [12.500, 15.000) = 98 
    [15.000, 17.500) = 19 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      3.138 ms/op
     p(50.0000) =      8.298 ms/op
     p(90.0000) =     11.221 ms/op
     p(95.0000) =     12.304 ms/op
     p(99.0000) =     18.282 ms/op
     p(99.9000) =     23.373 ms/op
     p(99.9900) =     24.150 ms/op
     p(99.9990) =     24.150 ms/op
     p(99.9999) =     24.150 ms/op
    p(100.0000) =     24.150 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.411          ops/ms
Client.existUser                       thrpt         13.496          ops/ms
Client.getUser                         thrpt          8.108          ops/ms
Client.listUser                        thrpt          4.129          ops/ms
Client.createUser                       avgt          2.867           ms/op
Client.existUser                        avgt          1.969           ms/op
Client.getUser                          avgt          3.157           ms/op
Client.listUser                         avgt          8.011           ms/op
Client.createUser                     sample  10985   2.913 ± 0.043   ms/op
Client.createUser:createUser·p0.00    sample          1.122           ms/op
Client.createUser:createUser·p0.50    sample          2.699           ms/op
Client.createUser:createUser·p0.90    sample          3.690           ms/op
Client.createUser:createUser·p0.95    sample          4.202           ms/op
Client.createUser:createUser·p0.99    sample         11.129           ms/op
Client.createUser:createUser·p0.999   sample         16.532           ms/op
Client.createUser:createUser·p0.9999  sample         16.646           ms/op
Client.createUser:createUser·p1.00    sample         16.646           ms/op
Client.existUser                      sample  17434   1.837 ± 0.011   ms/op
Client.existUser:existUser·p0.00      sample          0.565           ms/op
Client.existUser:existUser·p0.50      sample          1.815           ms/op
Client.existUser:existUser·p0.90      sample          2.286           ms/op
Client.existUser:existUser·p0.95      sample          2.474           ms/op
Client.existUser:existUser·p0.99      sample          3.266           ms/op
Client.existUser:existUser·p0.999     sample          4.932           ms/op
Client.existUser:existUser·p0.9999    sample          5.163           ms/op
Client.existUser:existUser·p1.00      sample          5.169           ms/op
Client.getUser                        sample  11208   2.863 ± 0.020   ms/op
Client.getUser:getUser·p0.00          sample          0.614           ms/op
Client.getUser:getUser·p0.50          sample          2.781           ms/op
Client.getUser:getUser·p0.90          sample          3.609           ms/op
Client.getUser:getUser·p0.95          sample          3.912           ms/op
Client.getUser:getUser·p0.99          sample          4.940           ms/op
Client.getUser:getUser·p0.999         sample          6.455           ms/op
Client.getUser:getUser·p0.9999        sample          8.525           ms/op
Client.getUser:getUser·p1.00          sample          8.651           ms/op
Client.listUser                       sample   3700   8.618 ± 0.128   ms/op
Client.listUser:listUser·p0.00        sample          3.138           ms/op
Client.listUser:listUser·p0.50        sample          8.298           ms/op
Client.listUser:listUser·p0.90        sample         11.221           ms/op
Client.listUser:listUser·p0.95        sample         12.304           ms/op
Client.listUser:listUser·p0.99        sample         18.282           ms/op
Client.listUser:listUser·p0.999       sample         23.373           ms/op
Client.listUser:listUser·p0.9999      sample         24.150           ms/op
Client.listUser:listUser·p1.00        sample         24.150           ms/op
