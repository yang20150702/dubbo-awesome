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
# Warmup Iteration   1: 2.039 ops/ms
Iteration   1: 5.608 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.608 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.275 ops/ms
Iteration   1: 12.772 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  12.772 ops/ms


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
# Warmup Iteration   1: 4.129 ops/ms
Iteration   1: 9.508 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  9.508 ops/ms


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
# Warmup Iteration   1: 2.123 ops/ms
Iteration   1: 3.230 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.230 ops/ms


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
# Warmup Iteration   1: 5.332 ±(99.9%) 0.077 ms/op
Iteration   1: 3.017 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.017 ms/op


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
# Warmup Iteration   1: 3.720 ±(99.9%) 0.041 ms/op
Iteration   1: 2.116 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  2.116 ms/op


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
# Warmup Iteration   1: 5.492 ±(99.9%) 0.100 ms/op
Iteration   1: 3.328 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.328 ms/op


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
# Warmup Iteration   1: 12.622 ±(99.9%) 0.245 ms/op
Iteration   1: 9.911 ±(99.9%) 0.103 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  9.911 ms/op


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
# Warmup Iteration   1: 5.551 ±(99.9%) 0.119 ms/op
Iteration   1: 3.076 ±(99.9%) 0.028 ms/op
                 createUser·p0.00:   1.035 ms/op
                 createUser·p0.50:   2.925 ms/op
                 createUser·p0.90:   3.621 ms/op
                 createUser·p0.95:   4.125 ms/op
                 createUser·p0.99:   5.703 ms/op
                 createUser·p0.999:  14.696 ms/op
                 createUser·p0.9999: 14.794 ms/op
                 createUser·p1.00:   14.795 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10377
  mean =      3.076 ±(99.9%) 0.028 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3 
    [ 1.250,  2.500) = 818 
    [ 2.500,  3.750) = 8713 
    [ 3.750,  5.000) = 618 
    [ 5.000,  6.250) = 143 
    [ 6.250,  7.500) = 45 
    [ 7.500,  8.750) = 5 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.035 ms/op
     p(50.0000) =      2.925 ms/op
     p(90.0000) =      3.621 ms/op
     p(95.0000) =      4.125 ms/op
     p(99.0000) =      5.703 ms/op
     p(99.9000) =     14.696 ms/op
     p(99.9900) =     14.794 ms/op
     p(99.9990) =     14.795 ms/op
     p(99.9999) =     14.795 ms/op
    p(100.0000) =     14.795 ms/op


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
# Warmup Iteration   1: 3.383 ±(99.9%) 0.101 ms/op
Iteration   1: 2.072 ±(99.9%) 0.028 ms/op
                 existUser·p0.00:   0.790 ms/op
                 existUser·p0.50:   1.907 ms/op
                 existUser·p0.90:   2.441 ms/op
                 existUser·p0.95:   2.855 ms/op
                 existUser·p0.99:   5.308 ms/op
                 existUser·p0.999:  19.848 ms/op
                 existUser·p0.9999: 20.761 ms/op
                 existUser·p1.00:   20.939 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 15427
  mean =      2.072 ±(99.9%) 0.028 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14061 
    [ 2.500,  5.000) = 1160 
    [ 5.000,  7.500) = 142 
    [ 7.500, 10.000) = 25 
    [10.000, 12.500) = 3 
    [12.500, 15.000) = 4 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.790 ms/op
     p(50.0000) =      1.907 ms/op
     p(90.0000) =      2.441 ms/op
     p(95.0000) =      2.855 ms/op
     p(99.0000) =      5.308 ms/op
     p(99.9000) =     19.848 ms/op
     p(99.9900) =     20.761 ms/op
     p(99.9990) =     20.939 ms/op
     p(99.9999) =     20.939 ms/op
    p(100.0000) =     20.939 ms/op


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

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 4.512 ±(99.9%) 0.110 ms/op
Iteration   1: 3.464 ±(99.9%) 0.027 ms/op
                 getUser·p0.00:   0.937 ms/op
                 getUser·p0.50:   3.473 ms/op
                 getUser·p0.90:   4.342 ms/op
                 getUser·p0.95:   4.678 ms/op
                 getUser·p0.99:   5.786 ms/op
                 getUser·p0.999:  7.162 ms/op
                 getUser·p0.9999: 8.086 ms/op
                 getUser·p1.00:   8.086 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 9242
  mean =      3.464 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 1 
    [1.000, 1.500) = 39 
    [1.500, 2.000) = 156 
    [2.000, 2.500) = 683 
    [2.500, 3.000) = 1640 
    [3.000, 3.500) = 2237 
    [3.500, 4.000) = 2642 
    [4.000, 4.500) = 1187 
    [4.500, 5.000) = 388 
    [5.000, 5.500) = 167 
    [5.500, 6.000) = 19 
    [6.000, 6.500) = 46 
    [6.500, 7.000) = 22 
    [7.000, 7.500) = 11 
    [7.500, 8.000) = 3 
    [8.000, 8.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.937 ms/op
     p(50.0000) =      3.473 ms/op
     p(90.0000) =      4.342 ms/op
     p(95.0000) =      4.678 ms/op
     p(99.0000) =      5.786 ms/op
     p(99.9000) =      7.162 ms/op
     p(99.9900) =      8.086 ms/op
     p(99.9990) =      8.086 ms/op
     p(99.9999) =      8.086 ms/op
    p(100.0000) =      8.086 ms/op


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

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 14.324 ±(99.9%) 0.493 ms/op
Iteration   1: 7.995 ±(99.9%) 0.106 ms/op
                 listUser·p0.00:   2.761 ms/op
                 listUser·p0.50:   7.709 ms/op
                 listUser·p0.90:   10.052 ms/op
                 listUser·p0.95:   11.125 ms/op
                 listUser·p0.99:   16.935 ms/op
                 listUser·p0.999:  21.951 ms/op
                 listUser·p0.9999: 35.979 ms/op
                 listUser·p1.00:   35.979 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 4004
  mean =      7.995 ±(99.9%) 0.106 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 104 
    [ 5.000,  7.500) = 1648 
    [ 7.500, 10.000) = 1837 
    [10.000, 12.500) = 302 
    [12.500, 15.000) = 60 
    [15.000, 17.500) = 29 
    [17.500, 20.000) = 19 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      2.761 ms/op
     p(50.0000) =      7.709 ms/op
     p(90.0000) =     10.052 ms/op
     p(95.0000) =     11.125 ms/op
     p(99.0000) =     16.935 ms/op
     p(99.9000) =     21.951 ms/op
     p(99.9900) =     35.979 ms/op
     p(99.9990) =     35.979 ms/op
     p(99.9999) =     35.979 ms/op
    p(100.0000) =     35.979 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.608          ops/ms
Client.existUser                       thrpt         12.772          ops/ms
Client.getUser                         thrpt          9.508          ops/ms
Client.listUser                        thrpt          3.230          ops/ms
Client.createUser                       avgt          3.017           ms/op
Client.existUser                        avgt          2.116           ms/op
Client.getUser                          avgt          3.328           ms/op
Client.listUser                         avgt          9.911           ms/op
Client.createUser                     sample  10377   3.076 ± 0.028   ms/op
Client.createUser:createUser·p0.00    sample          1.035           ms/op
Client.createUser:createUser·p0.50    sample          2.925           ms/op
Client.createUser:createUser·p0.90    sample          3.621           ms/op
Client.createUser:createUser·p0.95    sample          4.125           ms/op
Client.createUser:createUser·p0.99    sample          5.703           ms/op
Client.createUser:createUser·p0.999   sample         14.696           ms/op
Client.createUser:createUser·p0.9999  sample         14.794           ms/op
Client.createUser:createUser·p1.00    sample         14.795           ms/op
Client.existUser                      sample  15427   2.072 ± 0.028   ms/op
Client.existUser:existUser·p0.00      sample          0.790           ms/op
Client.existUser:existUser·p0.50      sample          1.907           ms/op
Client.existUser:existUser·p0.90      sample          2.441           ms/op
Client.existUser:existUser·p0.95      sample          2.855           ms/op
Client.existUser:existUser·p0.99      sample          5.308           ms/op
Client.existUser:existUser·p0.999     sample         19.848           ms/op
Client.existUser:existUser·p0.9999    sample         20.761           ms/op
Client.existUser:existUser·p1.00      sample         20.939           ms/op
Client.getUser                        sample   9242   3.464 ± 0.027   ms/op
Client.getUser:getUser·p0.00          sample          0.937           ms/op
Client.getUser:getUser·p0.50          sample          3.473           ms/op
Client.getUser:getUser·p0.90          sample          4.342           ms/op
Client.getUser:getUser·p0.95          sample          4.678           ms/op
Client.getUser:getUser·p0.99          sample          5.786           ms/op
Client.getUser:getUser·p0.999         sample          7.162           ms/op
Client.getUser:getUser·p0.9999        sample          8.086           ms/op
Client.getUser:getUser·p1.00          sample          8.086           ms/op
Client.listUser                       sample   4004   7.995 ± 0.106   ms/op
Client.listUser:listUser·p0.00        sample          2.761           ms/op
Client.listUser:listUser·p0.50        sample          7.709           ms/op
Client.listUser:listUser·p0.90        sample         10.052           ms/op
Client.listUser:listUser·p0.95        sample         11.125           ms/op
Client.listUser:listUser·p0.99        sample         16.935           ms/op
Client.listUser:listUser·p0.999       sample         21.951           ms/op
Client.listUser:listUser·p0.9999      sample         35.979           ms/op
Client.listUser:listUser·p1.00        sample         35.979           ms/op
