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
# Warmup Iteration   1: 2.118 ops/ms
Iteration   1: 4.925 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  4.925 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:19
# Fork: 1 of 1
# Warmup Iteration   1: 5.891 ops/ms
Iteration   1: 11.487 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  11.487 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:11
# Fork: 1 of 1
# Warmup Iteration   1: 4.335 ops/ms
Iteration   1: 8.265 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.265 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 2.106 ops/ms
Iteration   1: 4.076 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  4.076 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:57
# Fork: 1 of 1
# Warmup Iteration   1: 5.242 ±(99.9%) 0.088 ms/op
Iteration   1: 3.050 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.050 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:50
# Fork: 1 of 1
# Warmup Iteration   1: 3.174 ±(99.9%) 0.038 ms/op
Iteration   1: 1.860 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.860 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.542 ±(99.9%) 0.058 ms/op
Iteration   1: 3.169 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.169 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 12.482 ±(99.9%) 0.248 ms/op
Iteration   1: 8.417 ±(99.9%) 0.094 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.417 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 4.966 ±(99.9%) 0.118 ms/op
Iteration   1: 3.394 ±(99.9%) 0.041 ms/op
                 createUser·p0.00:   1.405 ms/op
                 createUser·p0.50:   3.219 ms/op
                 createUser·p0.90:   4.211 ms/op
                 createUser·p0.95:   4.637 ms/op
                 createUser·p0.99:   8.946 ms/op
                 createUser·p0.999:  13.795 ms/op
                 createUser·p0.9999: 13.877 ms/op
                 createUser·p1.00:   13.877 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 9413
  mean =      3.394 ±(99.9%) 0.041 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 1534 
    [ 2.500,  3.750) = 5382 
    [ 3.750,  5.000) = 2142 
    [ 5.000,  6.250) = 135 
    [ 6.250,  7.500) = 63 
    [ 7.500,  8.750) = 44 
    [ 8.750, 10.000) = 61 
    [10.000, 11.250) = 20 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 20 
    [13.750, 15.000) = 12 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.405 ms/op
     p(50.0000) =      3.219 ms/op
     p(90.0000) =      4.211 ms/op
     p(95.0000) =      4.637 ms/op
     p(99.0000) =      8.946 ms/op
     p(99.9000) =     13.795 ms/op
     p(99.9900) =     13.877 ms/op
     p(99.9990) =     13.877 ms/op
     p(99.9999) =     13.877 ms/op
    p(100.0000) =     13.877 ms/op


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
# Warmup Iteration   1: 3.574 ±(99.9%) 0.080 ms/op
Iteration   1: 2.158 ±(99.9%) 0.024 ms/op
                 existUser·p0.00:   0.591 ms/op
                 existUser·p0.50:   2.068 ms/op
                 existUser·p0.90:   2.732 ms/op
                 existUser·p0.95:   3.138 ms/op
                 existUser·p0.99:   5.528 ms/op
                 existUser·p0.999:  12.321 ms/op
                 existUser·p0.9999: 12.477 ms/op
                 existUser·p1.00:   12.485 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 14815
  mean =      2.158 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 403 
    [ 1.250,  2.500) = 11832 
    [ 2.500,  3.750) = 2260 
    [ 3.750,  5.000) = 144 
    [ 5.000,  6.250) = 111 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 22 
    [11.250, 12.500) = 42 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.591 ms/op
     p(50.0000) =      2.068 ms/op
     p(90.0000) =      2.732 ms/op
     p(95.0000) =      3.138 ms/op
     p(99.0000) =      5.528 ms/op
     p(99.9000) =     12.321 ms/op
     p(99.9900) =     12.477 ms/op
     p(99.9990) =     12.485 ms/op
     p(99.9999) =     12.485 ms/op
    p(100.0000) =     12.485 ms/op


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
# Warmup Iteration   1: 4.823 ±(99.9%) 0.134 ms/op
Iteration   1: 3.121 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   0.976 ms/op
                 getUser·p0.50:   3.068 ms/op
                 getUser·p0.90:   3.826 ms/op
                 getUser·p0.95:   4.194 ms/op
                 getUser·p0.99:   5.079 ms/op
                 getUser·p0.999:  7.543 ms/op
                 getUser·p0.9999: 9.093 ms/op
                 getUser·p1.00:   9.093 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10302
  mean =      3.121 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [ 0.000,  1.000) = 2 
    [ 1.000,  2.000) = 166 
    [ 2.000,  3.000) = 4356 
    [ 3.000,  4.000) = 5035 
    [ 4.000,  5.000) = 620 
    [ 5.000,  6.000) = 82 
    [ 6.000,  7.000) = 7 
    [ 7.000,  8.000) = 28 
    [ 8.000,  9.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.976 ms/op
     p(50.0000) =      3.068 ms/op
     p(90.0000) =      3.826 ms/op
     p(95.0000) =      4.194 ms/op
     p(99.0000) =      5.079 ms/op
     p(99.9000) =      7.543 ms/op
     p(99.9900) =      9.093 ms/op
     p(99.9990) =      9.093 ms/op
     p(99.9999) =      9.093 ms/op
    p(100.0000) =      9.093 ms/op


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
# Warmup Iteration   1: 11.324 ±(99.9%) 0.294 ms/op
Iteration   1: 8.435 ±(99.9%) 0.157 ms/op
                 listUser·p0.00:   2.253 ms/op
                 listUser·p0.50:   7.889 ms/op
                 listUser·p0.90:   11.387 ms/op
                 listUser·p0.95:   13.227 ms/op
                 listUser·p0.99:   21.629 ms/op
                 listUser·p0.999:  27.651 ms/op
                 listUser·p0.9999: 33.456 ms/op
                 listUser·p1.00:   33.456 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3793
  mean =      8.435 ±(99.9%) 0.157 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3 
    [ 2.500,  5.000) = 134 
    [ 5.000,  7.500) = 1436 
    [ 7.500, 10.000) = 1492 
    [10.000, 12.500) = 488 
    [12.500, 15.000) = 137 
    [15.000, 17.500) = 53 
    [17.500, 20.000) = 8 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 26 
    [27.500, 30.000) = 5 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.253 ms/op
     p(50.0000) =      7.889 ms/op
     p(90.0000) =     11.387 ms/op
     p(95.0000) =     13.227 ms/op
     p(99.0000) =     21.629 ms/op
     p(99.9000) =     27.651 ms/op
     p(99.9900) =     33.456 ms/op
     p(99.9990) =     33.456 ms/op
     p(99.9999) =     33.456 ms/op
    p(100.0000) =     33.456 ms/op


# Run complete. Total time: 00:01:26

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          4.925          ops/ms
Client.existUser                       thrpt         11.487          ops/ms
Client.getUser                         thrpt          8.265          ops/ms
Client.listUser                        thrpt          4.076          ops/ms
Client.createUser                       avgt          3.050           ms/op
Client.existUser                        avgt          1.860           ms/op
Client.getUser                          avgt          3.169           ms/op
Client.listUser                         avgt          8.417           ms/op
Client.createUser                     sample   9413   3.394 ± 0.041   ms/op
Client.createUser:createUser·p0.00    sample          1.405           ms/op
Client.createUser:createUser·p0.50    sample          3.219           ms/op
Client.createUser:createUser·p0.90    sample          4.211           ms/op
Client.createUser:createUser·p0.95    sample          4.637           ms/op
Client.createUser:createUser·p0.99    sample          8.946           ms/op
Client.createUser:createUser·p0.999   sample         13.795           ms/op
Client.createUser:createUser·p0.9999  sample         13.877           ms/op
Client.createUser:createUser·p1.00    sample         13.877           ms/op
Client.existUser                      sample  14815   2.158 ± 0.024   ms/op
Client.existUser:existUser·p0.00      sample          0.591           ms/op
Client.existUser:existUser·p0.50      sample          2.068           ms/op
Client.existUser:existUser·p0.90      sample          2.732           ms/op
Client.existUser:existUser·p0.95      sample          3.138           ms/op
Client.existUser:existUser·p0.99      sample          5.528           ms/op
Client.existUser:existUser·p0.999     sample         12.321           ms/op
Client.existUser:existUser·p0.9999    sample         12.477           ms/op
Client.existUser:existUser·p1.00      sample         12.485           ms/op
Client.getUser                        sample  10302   3.121 ± 0.021   ms/op
Client.getUser:getUser·p0.00          sample          0.976           ms/op
Client.getUser:getUser·p0.50          sample          3.068           ms/op
Client.getUser:getUser·p0.90          sample          3.826           ms/op
Client.getUser:getUser·p0.95          sample          4.194           ms/op
Client.getUser:getUser·p0.99          sample          5.079           ms/op
Client.getUser:getUser·p0.999         sample          7.543           ms/op
Client.getUser:getUser·p0.9999        sample          9.093           ms/op
Client.getUser:getUser·p1.00          sample          9.093           ms/op
Client.listUser                       sample   3793   8.435 ± 0.157   ms/op
Client.listUser:listUser·p0.00        sample          2.253           ms/op
Client.listUser:listUser·p0.50        sample          7.889           ms/op
Client.listUser:listUser·p0.90        sample         11.387           ms/op
Client.listUser:listUser·p0.95        sample         13.227           ms/op
Client.listUser:listUser·p0.99        sample         21.629           ms/op
Client.listUser:listUser·p0.999       sample         27.651           ms/op
Client.listUser:listUser·p0.9999      sample         33.456           ms/op
Client.listUser:listUser·p1.00        sample         33.456           ms/op
