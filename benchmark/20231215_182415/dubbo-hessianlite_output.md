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
# Warmup Iteration   1: 2.181 ops/ms
Iteration   1: 5.925 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.925 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 5.561 ops/ms
Iteration   1: 11.983 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  11.983 ops/ms


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
# Warmup Iteration   1: 3.624 ops/ms
Iteration   1: 7.931 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  7.931 ops/ms


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
# Warmup Iteration   1: 1.989 ops/ms
Iteration   1: 3.342 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.342 ops/ms


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
# Warmup Iteration   1: 5.580 ±(99.9%) 0.052 ms/op
Iteration   1: 3.311 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.311 ms/op


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
# Warmup Iteration   1: 3.722 ±(99.9%) 0.040 ms/op
Iteration   1: 2.135 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  2.135 ms/op


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
# Warmup Iteration   1: 4.782 ±(99.9%) 0.064 ms/op
Iteration   1: 3.636 ±(99.9%) 0.037 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.636 ms/op


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
# Warmup Iteration   1: 12.396 ±(99.9%) 0.237 ms/op
Iteration   1: 8.553 ±(99.9%) 0.072 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.553 ms/op


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
# Warmup Iteration   1: 5.309 ±(99.9%) 0.132 ms/op
Iteration   1: 3.003 ±(99.9%) 0.021 ms/op
                 createUser·p0.00:   1.108 ms/op
                 createUser·p0.50:   2.929 ms/op
                 createUser·p0.90:   3.551 ms/op
                 createUser·p0.95:   3.843 ms/op
                 createUser·p0.99:   5.135 ms/op
                 createUser·p0.999:  9.814 ms/op
                 createUser·p0.9999: 11.026 ms/op
                 createUser·p1.00:   11.043 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10655
  mean =      3.003 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [ 1.000,  2.000) = 168 
    [ 2.000,  3.000) = 6062 
    [ 3.000,  4.000) = 4014 
    [ 4.000,  5.000) = 272 
    [ 5.000,  6.000) = 87 
    [ 6.000,  7.000) = 12 
    [ 7.000,  8.000) = 8 
    [ 8.000,  9.000) = 0 
    [ 9.000, 10.000) = 28 
    [10.000, 11.000) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.108 ms/op
     p(50.0000) =      2.929 ms/op
     p(90.0000) =      3.551 ms/op
     p(95.0000) =      3.843 ms/op
     p(99.0000) =      5.135 ms/op
     p(99.9000) =      9.814 ms/op
     p(99.9900) =     11.026 ms/op
     p(99.9990) =     11.043 ms/op
     p(99.9999) =     11.043 ms/op
    p(100.0000) =     11.043 ms/op


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
# Warmup Iteration   1: 3.319 ±(99.9%) 0.076 ms/op
Iteration   1: 2.203 ±(99.9%) 0.027 ms/op
                 existUser·p0.00:   0.478 ms/op
                 existUser·p0.50:   2.101 ms/op
                 existUser·p0.90:   2.585 ms/op
                 existUser·p0.95:   2.769 ms/op
                 existUser·p0.99:   5.382 ms/op
                 existUser·p0.999:  15.319 ms/op
                 existUser·p0.9999: 16.240 ms/op
                 existUser·p1.00:   16.351 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 14510
  mean =      2.203 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 193 
    [ 1.250,  2.500) = 12242 
    [ 2.500,  3.750) = 1872 
    [ 3.750,  5.000) = 42 
    [ 5.000,  6.250) = 71 
    [ 6.250,  7.500) = 21 
    [ 7.500,  8.750) = 4 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 24 
    [15.000, 16.250) = 38 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.478 ms/op
     p(50.0000) =      2.101 ms/op
     p(90.0000) =      2.585 ms/op
     p(95.0000) =      2.769 ms/op
     p(99.0000) =      5.382 ms/op
     p(99.9000) =     15.319 ms/op
     p(99.9900) =     16.240 ms/op
     p(99.9990) =     16.351 ms/op
     p(99.9999) =     16.351 ms/op
    p(100.0000) =     16.351 ms/op


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
# Warmup Iteration   1: 5.115 ±(99.9%) 0.145 ms/op
Iteration   1: 3.144 ±(99.9%) 0.025 ms/op
                 getUser·p0.00:   0.768 ms/op
                 getUser·p0.50:   3.088 ms/op
                 getUser·p0.90:   4.030 ms/op
                 getUser·p0.95:   4.284 ms/op
                 getUser·p0.99:   5.628 ms/op
                 getUser·p0.999:  6.704 ms/op
                 getUser·p0.9999: 8.300 ms/op
                 getUser·p1.00:   8.315 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10167
  mean =      3.144 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 15 
    [1.000, 1.500) = 70 
    [1.500, 2.000) = 270 
    [2.000, 2.500) = 1747 
    [2.500, 3.000) = 2583 
    [3.000, 3.500) = 2333 
    [3.500, 4.000) = 2057 
    [4.000, 4.500) = 795 
    [4.500, 5.000) = 116 
    [5.000, 5.500) = 60 
    [5.500, 6.000) = 78 
    [6.000, 6.500) = 23 
    [6.500, 7.000) = 16 
    [7.000, 7.500) = 3 
    [7.500, 8.000) = 0 
    [8.000, 8.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.768 ms/op
     p(50.0000) =      3.088 ms/op
     p(90.0000) =      4.030 ms/op
     p(95.0000) =      4.284 ms/op
     p(99.0000) =      5.628 ms/op
     p(99.9000) =      6.704 ms/op
     p(99.9900) =      8.300 ms/op
     p(99.9990) =      8.315 ms/op
     p(99.9999) =      8.315 ms/op
    p(100.0000) =      8.315 ms/op


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
# Warmup Iteration   1: 14.232 ±(99.9%) 0.514 ms/op
Iteration   1: 9.370 ±(99.9%) 0.422 ms/op
                 listUser·p0.00:   1.473 ms/op
                 listUser·p0.50:   8.184 ms/op
                 listUser·p0.90:   12.706 ms/op
                 listUser·p0.95:   15.167 ms/op
                 listUser·p0.99:   27.712 ms/op
                 listUser·p0.999:  101.123 ms/op
                 listUser·p0.9999: 110.100 ms/op
                 listUser·p1.00:   110.100 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3404
  mean =      9.370 ±(99.9%) 0.422 ms/op

  Histogram, ms/op:
    [  0.000,  12.500) = 3045 
    [ 12.500,  25.000) = 312 
    [ 25.000,  37.500) = 15 
    [ 37.500,  50.000) = 0 
    [ 50.000,  62.500) = 0 
    [ 62.500,  75.000) = 24 
    [ 75.000,  87.500) = 2 
    [ 87.500, 100.000) = 3 
    [100.000, 112.500) = 3 
    [112.500, 125.000) = 0 
    [125.000, 137.500) = 0 
    [137.500, 150.000) = 0 
    [150.000, 162.500) = 0 
    [162.500, 175.000) = 0 
    [175.000, 187.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.473 ms/op
     p(50.0000) =      8.184 ms/op
     p(90.0000) =     12.706 ms/op
     p(95.0000) =     15.167 ms/op
     p(99.0000) =     27.712 ms/op
     p(99.9000) =    101.123 ms/op
     p(99.9900) =    110.100 ms/op
     p(99.9990) =    110.100 ms/op
     p(99.9999) =    110.100 ms/op
    p(100.0000) =    110.100 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt    Score   Error   Units
Client.createUser                      thrpt           5.925          ops/ms
Client.existUser                       thrpt          11.983          ops/ms
Client.getUser                         thrpt           7.931          ops/ms
Client.listUser                        thrpt           3.342          ops/ms
Client.createUser                       avgt           3.311           ms/op
Client.existUser                        avgt           2.135           ms/op
Client.getUser                          avgt           3.636           ms/op
Client.listUser                         avgt           8.553           ms/op
Client.createUser                     sample  10655    3.003 ± 0.021   ms/op
Client.createUser:createUser·p0.00    sample           1.108           ms/op
Client.createUser:createUser·p0.50    sample           2.929           ms/op
Client.createUser:createUser·p0.90    sample           3.551           ms/op
Client.createUser:createUser·p0.95    sample           3.843           ms/op
Client.createUser:createUser·p0.99    sample           5.135           ms/op
Client.createUser:createUser·p0.999   sample           9.814           ms/op
Client.createUser:createUser·p0.9999  sample          11.026           ms/op
Client.createUser:createUser·p1.00    sample          11.043           ms/op
Client.existUser                      sample  14510    2.203 ± 0.027   ms/op
Client.existUser:existUser·p0.00      sample           0.478           ms/op
Client.existUser:existUser·p0.50      sample           2.101           ms/op
Client.existUser:existUser·p0.90      sample           2.585           ms/op
Client.existUser:existUser·p0.95      sample           2.769           ms/op
Client.existUser:existUser·p0.99      sample           5.382           ms/op
Client.existUser:existUser·p0.999     sample          15.319           ms/op
Client.existUser:existUser·p0.9999    sample          16.240           ms/op
Client.existUser:existUser·p1.00      sample          16.351           ms/op
Client.getUser                        sample  10167    3.144 ± 0.025   ms/op
Client.getUser:getUser·p0.00          sample           0.768           ms/op
Client.getUser:getUser·p0.50          sample           3.088           ms/op
Client.getUser:getUser·p0.90          sample           4.030           ms/op
Client.getUser:getUser·p0.95          sample           4.284           ms/op
Client.getUser:getUser·p0.99          sample           5.628           ms/op
Client.getUser:getUser·p0.999         sample           6.704           ms/op
Client.getUser:getUser·p0.9999        sample           8.300           ms/op
Client.getUser:getUser·p1.00          sample           8.315           ms/op
Client.listUser                       sample   3404    9.370 ± 0.422   ms/op
Client.listUser:listUser·p0.00        sample           1.473           ms/op
Client.listUser:listUser·p0.50        sample           8.184           ms/op
Client.listUser:listUser·p0.90        sample          12.706           ms/op
Client.listUser:listUser·p0.95        sample          15.167           ms/op
Client.listUser:listUser·p0.99        sample          27.712           ms/op
Client.listUser:listUser·p0.999       sample         101.123           ms/op
Client.listUser:listUser·p0.9999      sample         110.100           ms/op
Client.listUser:listUser·p1.00        sample         110.100           ms/op
