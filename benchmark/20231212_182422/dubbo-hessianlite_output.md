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
# Warmup Iteration   1: 2.549 ops/ms
Iteration   1: 6.665 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.665 ops/ms


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
# Warmup Iteration   1: 5.384 ops/ms
Iteration   1: 11.854 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  11.854 ops/ms


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
# Warmup Iteration   1: 4.208 ops/ms
Iteration   1: 8.854 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.854 ops/ms


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
# Warmup Iteration   1: 2.091 ops/ms
Iteration   1: 3.695 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.695 ops/ms


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
# Warmup Iteration   1: 4.936 ±(99.9%) 0.060 ms/op
Iteration   1: 2.803 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.803 ms/op


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
# Warmup Iteration   1: 3.127 ±(99.9%) 0.038 ms/op
Iteration   1: 1.797 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.797 ms/op


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
# Warmup Iteration   1: 4.405 ±(99.9%) 0.049 ms/op
Iteration   1: 3.162 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
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
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 12.784 ±(99.9%) 0.250 ms/op
Iteration   1: 8.908 ±(99.9%) 0.118 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.908 ms/op


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
# Warmup Iteration   1: 5.046 ±(99.9%) 0.102 ms/op
Iteration   1: 3.225 ±(99.9%) 0.039 ms/op
                 createUser·p0.00:   1.037 ms/op
                 createUser·p0.50:   2.908 ms/op
                 createUser·p0.90:   4.170 ms/op
                 createUser·p0.95:   4.645 ms/op
                 createUser·p0.99:   7.405 ms/op
                 createUser·p0.999:  14.172 ms/op
                 createUser·p0.9999: 14.221 ms/op
                 createUser·p1.00:   14.221 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 9901
  mean =      3.225 ±(99.9%) 0.039 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 6 
    [ 1.250,  2.500) = 1305 
    [ 2.500,  3.750) = 6664 
    [ 3.750,  5.000) = 1555 
    [ 5.000,  6.250) = 128 
    [ 6.250,  7.500) = 148 
    [ 7.500,  8.750) = 17 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 20 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 47 
    [13.750, 15.000) = 10 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.037 ms/op
     p(50.0000) =      2.908 ms/op
     p(90.0000) =      4.170 ms/op
     p(95.0000) =      4.645 ms/op
     p(99.0000) =      7.405 ms/op
     p(99.9000) =     14.172 ms/op
     p(99.9900) =     14.221 ms/op
     p(99.9990) =     14.221 ms/op
     p(99.9999) =     14.221 ms/op
    p(100.0000) =     14.221 ms/op


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
# Warmup Iteration   1: 3.122 ±(99.9%) 0.087 ms/op
Iteration   1: 1.970 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   0.368 ms/op
                 existUser·p0.50:   1.894 ms/op
                 existUser·p0.90:   2.707 ms/op
                 existUser·p0.95:   2.912 ms/op
                 existUser·p0.99:   3.486 ms/op
                 existUser·p0.999:  5.621 ms/op
                 existUser·p0.9999: 6.456 ms/op
                 existUser·p1.00:   6.537 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 16228
  mean =      1.970 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 28 
    [0.500, 1.000) = 144 
    [1.000, 1.500) = 3657 
    [1.500, 2.000) = 5229 
    [2.000, 2.500) = 4290 
    [2.500, 3.000) = 2249 
    [3.000, 3.500) = 482 
    [3.500, 4.000) = 53 
    [4.000, 4.500) = 15 
    [4.500, 5.000) = 17 
    [5.000, 5.500) = 39 
    [5.500, 6.000) = 18 
    [6.000, 6.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.368 ms/op
     p(50.0000) =      1.894 ms/op
     p(90.0000) =      2.707 ms/op
     p(95.0000) =      2.912 ms/op
     p(99.0000) =      3.486 ms/op
     p(99.9000) =      5.621 ms/op
     p(99.9900) =      6.456 ms/op
     p(99.9990) =      6.537 ms/op
     p(99.9999) =      6.537 ms/op
    p(100.0000) =      6.537 ms/op


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
# Warmup Iteration   1: 4.421 ±(99.9%) 0.107 ms/op
Iteration   1: 2.823 ±(99.9%) 0.039 ms/op
                 getUser·p0.00:   0.703 ms/op
                 getUser·p0.50:   2.613 ms/op
                 getUser·p0.90:   3.690 ms/op
                 getUser·p0.95:   4.059 ms/op
                 getUser·p0.99:   5.183 ms/op
                 getUser·p0.999:  22.839 ms/op
                 getUser·p0.9999: 24.014 ms/op
                 getUser·p1.00:   24.019 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 11417
  mean =      2.823 ±(99.9%) 0.039 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5047 
    [ 2.500,  5.000) = 6249 
    [ 5.000,  7.500) = 89 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.703 ms/op
     p(50.0000) =      2.613 ms/op
     p(90.0000) =      3.690 ms/op
     p(95.0000) =      4.059 ms/op
     p(99.0000) =      5.183 ms/op
     p(99.9000) =     22.839 ms/op
     p(99.9900) =     24.014 ms/op
     p(99.9990) =     24.019 ms/op
     p(99.9999) =     24.019 ms/op
    p(100.0000) =     24.019 ms/op


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
# Warmup Iteration   1: 13.435 ±(99.9%) 0.587 ms/op
Iteration   1: 8.042 ±(99.9%) 0.108 ms/op
                 listUser·p0.00:   2.785 ms/op
                 listUser·p0.50:   7.733 ms/op
                 listUser·p0.90:   9.801 ms/op
                 listUser·p0.95:   11.053 ms/op
                 listUser·p0.99:   18.252 ms/op
                 listUser·p0.999:  23.673 ms/op
                 listUser·p0.9999: 25.231 ms/op
                 listUser·p1.00:   25.231 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3987
  mean =      8.042 ±(99.9%) 0.108 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 46 
    [ 5.000,  7.500) = 1624 
    [ 7.500, 10.000) = 1967 
    [10.000, 12.500) = 231 
    [12.500, 15.000) = 44 
    [15.000, 17.500) = 20 
    [17.500, 20.000) = 41 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      2.785 ms/op
     p(50.0000) =      7.733 ms/op
     p(90.0000) =      9.801 ms/op
     p(95.0000) =     11.053 ms/op
     p(99.0000) =     18.252 ms/op
     p(99.9000) =     23.673 ms/op
     p(99.9900) =     25.231 ms/op
     p(99.9990) =     25.231 ms/op
     p(99.9999) =     25.231 ms/op
    p(100.0000) =     25.231 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.665          ops/ms
Client.existUser                       thrpt         11.854          ops/ms
Client.getUser                         thrpt          8.854          ops/ms
Client.listUser                        thrpt          3.695          ops/ms
Client.createUser                       avgt          2.803           ms/op
Client.existUser                        avgt          1.797           ms/op
Client.getUser                          avgt          3.162           ms/op
Client.listUser                         avgt          8.908           ms/op
Client.createUser                     sample   9901   3.225 ± 0.039   ms/op
Client.createUser:createUser·p0.00    sample          1.037           ms/op
Client.createUser:createUser·p0.50    sample          2.908           ms/op
Client.createUser:createUser·p0.90    sample          4.170           ms/op
Client.createUser:createUser·p0.95    sample          4.645           ms/op
Client.createUser:createUser·p0.99    sample          7.405           ms/op
Client.createUser:createUser·p0.999   sample         14.172           ms/op
Client.createUser:createUser·p0.9999  sample         14.221           ms/op
Client.createUser:createUser·p1.00    sample         14.221           ms/op
Client.existUser                      sample  16228   1.970 ± 0.015   ms/op
Client.existUser:existUser·p0.00      sample          0.368           ms/op
Client.existUser:existUser·p0.50      sample          1.894           ms/op
Client.existUser:existUser·p0.90      sample          2.707           ms/op
Client.existUser:existUser·p0.95      sample          2.912           ms/op
Client.existUser:existUser·p0.99      sample          3.486           ms/op
Client.existUser:existUser·p0.999     sample          5.621           ms/op
Client.existUser:existUser·p0.9999    sample          6.456           ms/op
Client.existUser:existUser·p1.00      sample          6.537           ms/op
Client.getUser                        sample  11417   2.823 ± 0.039   ms/op
Client.getUser:getUser·p0.00          sample          0.703           ms/op
Client.getUser:getUser·p0.50          sample          2.613           ms/op
Client.getUser:getUser·p0.90          sample          3.690           ms/op
Client.getUser:getUser·p0.95          sample          4.059           ms/op
Client.getUser:getUser·p0.99          sample          5.183           ms/op
Client.getUser:getUser·p0.999         sample         22.839           ms/op
Client.getUser:getUser·p0.9999        sample         24.014           ms/op
Client.getUser:getUser·p1.00          sample         24.019           ms/op
Client.listUser                       sample   3987   8.042 ± 0.108   ms/op
Client.listUser:listUser·p0.00        sample          2.785           ms/op
Client.listUser:listUser·p0.50        sample          7.733           ms/op
Client.listUser:listUser·p0.90        sample          9.801           ms/op
Client.listUser:listUser·p0.95        sample         11.053           ms/op
Client.listUser:listUser·p0.99        sample         18.252           ms/op
Client.listUser:listUser·p0.999       sample         23.673           ms/op
Client.listUser:listUser·p0.9999      sample         25.231           ms/op
Client.listUser:listUser·p1.00        sample         25.231           ms/op
