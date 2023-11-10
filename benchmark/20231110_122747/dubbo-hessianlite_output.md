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
# Warmup Iteration   1: 2.260 ops/ms
Iteration   1: 6.013 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.013 ops/ms


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
# Warmup Iteration   1: 6.361 ops/ms
Iteration   1: 12.572 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  12.572 ops/ms


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
# Warmup Iteration   1: 4.484 ops/ms
Iteration   1: 7.705 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  7.705 ops/ms


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
# Warmup Iteration   1: 1.982 ops/ms
Iteration   1: 3.505 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.505 ops/ms


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
# Warmup Iteration   1: 5.099 ±(99.9%) 0.070 ms/op
Iteration   1: 3.027 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.027 ms/op


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
# Warmup Iteration   1: 3.038 ±(99.9%) 0.031 ms/op
Iteration   1: 1.735 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.735 ms/op


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
# Warmup Iteration   1: 4.797 ±(99.9%) 0.062 ms/op
Iteration   1: 3.275 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.275 ms/op


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
# Warmup Iteration   1: 10.990 ±(99.9%) 0.149 ms/op
Iteration   1: 7.741 ±(99.9%) 0.078 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  7.741 ms/op


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
# Warmup Iteration   1: 4.900 ±(99.9%) 0.096 ms/op
Iteration   1: 3.160 ±(99.9%) 0.038 ms/op
                 createUser·p0.00:   0.912 ms/op
                 createUser·p0.50:   2.998 ms/op
                 createUser·p0.90:   3.737 ms/op
                 createUser·p0.95:   4.035 ms/op
                 createUser·p0.99:   9.896 ms/op
                 createUser·p0.999:  12.894 ms/op
                 createUser·p0.9999: 13.975 ms/op
                 createUser·p1.00:   13.976 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10116
  mean =      3.160 ±(99.9%) 0.038 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 7 
    [ 1.250,  2.500) = 1470 
    [ 2.500,  3.750) = 7664 
    [ 3.750,  5.000) = 720 
    [ 5.000,  6.250) = 18 
    [ 6.250,  7.500) = 61 
    [ 7.500,  8.750) = 20 
    [ 8.750, 10.000) = 59 
    [10.000, 11.250) = 20 
    [11.250, 12.500) = 47 
    [12.500, 13.750) = 28 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.912 ms/op
     p(50.0000) =      2.998 ms/op
     p(90.0000) =      3.737 ms/op
     p(95.0000) =      4.035 ms/op
     p(99.0000) =      9.896 ms/op
     p(99.9000) =     12.894 ms/op
     p(99.9900) =     13.975 ms/op
     p(99.9990) =     13.976 ms/op
     p(99.9999) =     13.976 ms/op
    p(100.0000) =     13.976 ms/op


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
# Warmup Iteration   1: 3.233 ±(99.9%) 0.068 ms/op
Iteration   1: 1.865 ±(99.9%) 0.022 ms/op
                 existUser·p0.00:   0.521 ms/op
                 existUser·p0.50:   1.786 ms/op
                 existUser·p0.90:   2.195 ms/op
                 existUser·p0.95:   2.388 ms/op
                 existUser·p0.99:   4.575 ms/op
                 existUser·p0.999:  14.516 ms/op
                 existUser·p0.9999: 14.652 ms/op
                 existUser·p1.00:   14.664 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 17357
  mean =      1.865 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 823 
    [ 1.250,  2.500) = 15861 
    [ 2.500,  3.750) = 363 
    [ 3.750,  5.000) = 190 
    [ 5.000,  6.250) = 56 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.521 ms/op
     p(50.0000) =      1.786 ms/op
     p(90.0000) =      2.195 ms/op
     p(95.0000) =      2.388 ms/op
     p(99.0000) =      4.575 ms/op
     p(99.9000) =     14.516 ms/op
     p(99.9900) =     14.652 ms/op
     p(99.9990) =     14.664 ms/op
     p(99.9999) =     14.664 ms/op
    p(100.0000) =     14.664 ms/op


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
# Warmup Iteration   1: 4.206 ±(99.9%) 0.090 ms/op
Iteration   1: 3.061 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   0.924 ms/op
                 getUser·p0.50:   3.031 ms/op
                 getUser·p0.90:   3.895 ms/op
                 getUser·p0.95:   4.174 ms/op
                 getUser·p0.99:   5.759 ms/op
                 getUser·p0.999:  6.576 ms/op
                 getUser·p0.9999: 8.378 ms/op
                 getUser·p1.00:   8.405 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10440
  mean =      3.061 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 2 
    [1.000, 1.500) = 26 
    [1.500, 2.000) = 470 
    [2.000, 2.500) = 2170 
    [2.500, 3.000) = 2426 
    [3.000, 3.500) = 2478 
    [3.500, 4.000) = 2062 
    [4.000, 4.500) = 506 
    [4.500, 5.000) = 125 
    [5.000, 5.500) = 50 
    [5.500, 6.000) = 83 
    [6.000, 6.500) = 31 
    [6.500, 7.000) = 4 
    [7.000, 7.500) = 2 
    [7.500, 8.000) = 4 
    [8.000, 8.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.924 ms/op
     p(50.0000) =      3.031 ms/op
     p(90.0000) =      3.895 ms/op
     p(95.0000) =      4.174 ms/op
     p(99.0000) =      5.759 ms/op
     p(99.9000) =      6.576 ms/op
     p(99.9900) =      8.378 ms/op
     p(99.9990) =      8.405 ms/op
     p(99.9999) =      8.405 ms/op
    p(100.0000) =      8.405 ms/op


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
# Warmup Iteration   1: 13.082 ±(99.9%) 0.629 ms/op
Iteration   1: 8.683 ±(99.9%) 0.132 ms/op
                 listUser·p0.00:   2.054 ms/op
                 listUser·p0.50:   8.339 ms/op
                 listUser·p0.90:   11.420 ms/op
                 listUser·p0.95:   12.435 ms/op
                 listUser·p0.99:   16.289 ms/op
                 listUser·p0.999:  25.370 ms/op
                 listUser·p0.9999: 31.326 ms/op
                 listUser·p1.00:   31.326 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3759
  mean =      8.683 ±(99.9%) 0.132 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5 
    [ 2.500,  5.000) = 104 
    [ 5.000,  7.500) = 1024 
    [ 7.500, 10.000) = 1800 
    [10.000, 12.500) = 646 
    [12.500, 15.000) = 133 
    [15.000, 17.500) = 11 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 6 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.054 ms/op
     p(50.0000) =      8.339 ms/op
     p(90.0000) =     11.420 ms/op
     p(95.0000) =     12.435 ms/op
     p(99.0000) =     16.289 ms/op
     p(99.9000) =     25.370 ms/op
     p(99.9900) =     31.326 ms/op
     p(99.9990) =     31.326 ms/op
     p(99.9999) =     31.326 ms/op
    p(100.0000) =     31.326 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.013          ops/ms
Client.existUser                       thrpt         12.572          ops/ms
Client.getUser                         thrpt          7.705          ops/ms
Client.listUser                        thrpt          3.505          ops/ms
Client.createUser                       avgt          3.027           ms/op
Client.existUser                        avgt          1.735           ms/op
Client.getUser                          avgt          3.275           ms/op
Client.listUser                         avgt          7.741           ms/op
Client.createUser                     sample  10116   3.160 ± 0.038   ms/op
Client.createUser:createUser·p0.00    sample          0.912           ms/op
Client.createUser:createUser·p0.50    sample          2.998           ms/op
Client.createUser:createUser·p0.90    sample          3.737           ms/op
Client.createUser:createUser·p0.95    sample          4.035           ms/op
Client.createUser:createUser·p0.99    sample          9.896           ms/op
Client.createUser:createUser·p0.999   sample         12.894           ms/op
Client.createUser:createUser·p0.9999  sample         13.975           ms/op
Client.createUser:createUser·p1.00    sample         13.976           ms/op
Client.existUser                      sample  17357   1.865 ± 0.022   ms/op
Client.existUser:existUser·p0.00      sample          0.521           ms/op
Client.existUser:existUser·p0.50      sample          1.786           ms/op
Client.existUser:existUser·p0.90      sample          2.195           ms/op
Client.existUser:existUser·p0.95      sample          2.388           ms/op
Client.existUser:existUser·p0.99      sample          4.575           ms/op
Client.existUser:existUser·p0.999     sample         14.516           ms/op
Client.existUser:existUser·p0.9999    sample         14.652           ms/op
Client.existUser:existUser·p1.00      sample         14.664           ms/op
Client.getUser                        sample  10440   3.061 ± 0.024   ms/op
Client.getUser:getUser·p0.00          sample          0.924           ms/op
Client.getUser:getUser·p0.50          sample          3.031           ms/op
Client.getUser:getUser·p0.90          sample          3.895           ms/op
Client.getUser:getUser·p0.95          sample          4.174           ms/op
Client.getUser:getUser·p0.99          sample          5.759           ms/op
Client.getUser:getUser·p0.999         sample          6.576           ms/op
Client.getUser:getUser·p0.9999        sample          8.378           ms/op
Client.getUser:getUser·p1.00          sample          8.405           ms/op
Client.listUser                       sample   3759   8.683 ± 0.132   ms/op
Client.listUser:listUser·p0.00        sample          2.054           ms/op
Client.listUser:listUser·p0.50        sample          8.339           ms/op
Client.listUser:listUser·p0.90        sample         11.420           ms/op
Client.listUser:listUser·p0.95        sample         12.435           ms/op
Client.listUser:listUser·p0.99        sample         16.289           ms/op
Client.listUser:listUser·p0.999       sample         25.370           ms/op
Client.listUser:listUser·p0.9999      sample         31.326           ms/op
Client.listUser:listUser·p1.00        sample         31.326           ms/op
