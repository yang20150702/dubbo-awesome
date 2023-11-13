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
# Warmup Iteration   1: 2.646 ops/ms
Iteration   1: 6.613 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.613 ops/ms


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
# Warmup Iteration   1: 7.054 ops/ms
Iteration   1: 13.230 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  13.230 ops/ms


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
# Warmup Iteration   1: 3.982 ops/ms
Iteration   1: 8.821 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.821 ops/ms


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
# Warmup Iteration   1: 2.132 ops/ms
Iteration   1: 3.616 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.616 ops/ms


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
# Warmup Iteration   1: 6.493 ±(99.9%) 0.087 ms/op
Iteration   1: 3.135 ±(99.9%) 0.024 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.135 ms/op


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
# Warmup Iteration   1: 4.158 ±(99.9%) 0.042 ms/op
Iteration   1: 2.255 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  2.255 ms/op


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
# Warmup Iteration   1: 4.754 ±(99.9%) 0.055 ms/op
Iteration   1: 3.238 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.238 ms/op


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
# Warmup Iteration   1: 10.618 ±(99.9%) 0.187 ms/op
Iteration   1: 8.412 ±(99.9%) 0.081 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.412 ms/op


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
# Warmup Iteration   1: 4.958 ±(99.9%) 0.097 ms/op
Iteration   1: 3.260 ±(99.9%) 0.044 ms/op
                 createUser·p0.00:   1.174 ms/op
                 createUser·p0.50:   3.006 ms/op
                 createUser·p0.90:   3.919 ms/op
                 createUser·p0.95:   4.763 ms/op
                 createUser·p0.99:   10.379 ms/op
                 createUser·p0.999:  14.637 ms/op
                 createUser·p0.9999: 20.480 ms/op
                 createUser·p1.00:   20.480 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 9850
  mean =      3.260 ±(99.9%) 0.044 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1283 
    [ 2.500,  5.000) = 8114 
    [ 5.000,  7.500) = 231 
    [ 7.500, 10.000) = 114 
    [10.000, 12.500) = 56 
    [12.500, 15.000) = 43 
    [15.000, 17.500) = 8 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.174 ms/op
     p(50.0000) =      3.006 ms/op
     p(90.0000) =      3.919 ms/op
     p(95.0000) =      4.763 ms/op
     p(99.0000) =     10.379 ms/op
     p(99.9000) =     14.637 ms/op
     p(99.9900) =     20.480 ms/op
     p(99.9990) =     20.480 ms/op
     p(99.9999) =     20.480 ms/op
    p(100.0000) =     20.480 ms/op


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
# Warmup Iteration   1: 3.094 ±(99.9%) 0.067 ms/op
Iteration   1: 1.957 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   0.396 ms/op
                 existUser·p0.50:   1.905 ms/op
                 existUser·p0.90:   2.339 ms/op
                 existUser·p0.95:   2.503 ms/op
                 existUser·p0.99:   3.734 ms/op
                 existUser·p0.999:  15.450 ms/op
                 existUser·p0.9999: 15.593 ms/op
                 existUser·p1.00:   15.614 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 16339
  mean =      1.957 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 658 
    [ 1.250,  2.500) = 14859 
    [ 2.500,  3.750) = 662 
    [ 3.750,  5.000) = 37 
    [ 5.000,  6.250) = 91 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 7 
    [15.000, 16.250) = 25 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.396 ms/op
     p(50.0000) =      1.905 ms/op
     p(90.0000) =      2.339 ms/op
     p(95.0000) =      2.503 ms/op
     p(99.0000) =      3.734 ms/op
     p(99.9000) =     15.450 ms/op
     p(99.9900) =     15.593 ms/op
     p(99.9990) =     15.614 ms/op
     p(99.9999) =     15.614 ms/op
    p(100.0000) =     15.614 ms/op


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
# Warmup Iteration   1: 4.164 ±(99.9%) 0.081 ms/op
Iteration   1: 3.175 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   0.787 ms/op
                 getUser·p0.50:   3.154 ms/op
                 getUser·p0.90:   4.084 ms/op
                 getUser·p0.95:   4.342 ms/op
                 getUser·p0.99:   5.014 ms/op
                 getUser·p0.999:  6.798 ms/op
                 getUser·p0.9999: 7.126 ms/op
                 getUser·p1.00:   7.127 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10074
  mean =      3.175 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 2 
    [1.000, 1.500) = 40 
    [1.500, 2.000) = 217 
    [2.000, 2.500) = 1782 
    [2.500, 3.000) = 2270 
    [3.000, 3.500) = 2418 
    [3.500, 4.000) = 2087 
    [4.000, 4.500) = 918 
    [4.500, 5.000) = 238 
    [5.000, 5.500) = 71 
    [5.500, 6.000) = 5 
    [6.000, 6.500) = 12 
    [6.500, 7.000) = 11 
    [7.000, 7.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.787 ms/op
     p(50.0000) =      3.154 ms/op
     p(90.0000) =      4.084 ms/op
     p(95.0000) =      4.342 ms/op
     p(99.0000) =      5.014 ms/op
     p(99.9000) =      6.798 ms/op
     p(99.9900) =      7.126 ms/op
     p(99.9990) =      7.127 ms/op
     p(99.9999) =      7.127 ms/op
    p(100.0000) =      7.127 ms/op


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
# Warmup Iteration   1: 12.779 ±(99.9%) 0.494 ms/op
Iteration   1: 8.742 ±(99.9%) 0.131 ms/op
                 listUser·p0.00:   3.154 ms/op
                 listUser·p0.50:   8.405 ms/op
                 listUser·p0.90:   11.698 ms/op
                 listUser·p0.95:   13.133 ms/op
                 listUser·p0.99:   16.122 ms/op
                 listUser·p0.999:  21.518 ms/op
                 listUser·p0.9999: 24.052 ms/op
                 listUser·p1.00:   24.052 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3661
  mean =      8.742 ±(99.9%) 0.131 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 98 
    [ 5.000,  7.500) = 1105 
    [ 7.500, 10.000) = 1539 
    [10.000, 12.500) = 672 
    [12.500, 15.000) = 177 
    [15.000, 17.500) = 56 
    [17.500, 20.000) = 10 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      3.154 ms/op
     p(50.0000) =      8.405 ms/op
     p(90.0000) =     11.698 ms/op
     p(95.0000) =     13.133 ms/op
     p(99.0000) =     16.122 ms/op
     p(99.9000) =     21.518 ms/op
     p(99.9900) =     24.052 ms/op
     p(99.9990) =     24.052 ms/op
     p(99.9999) =     24.052 ms/op
    p(100.0000) =     24.052 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.613          ops/ms
Client.existUser                       thrpt         13.230          ops/ms
Client.getUser                         thrpt          8.821          ops/ms
Client.listUser                        thrpt          3.616          ops/ms
Client.createUser                       avgt          3.135           ms/op
Client.existUser                        avgt          2.255           ms/op
Client.getUser                          avgt          3.238           ms/op
Client.listUser                         avgt          8.412           ms/op
Client.createUser                     sample   9850   3.260 ± 0.044   ms/op
Client.createUser:createUser·p0.00    sample          1.174           ms/op
Client.createUser:createUser·p0.50    sample          3.006           ms/op
Client.createUser:createUser·p0.90    sample          3.919           ms/op
Client.createUser:createUser·p0.95    sample          4.763           ms/op
Client.createUser:createUser·p0.99    sample         10.379           ms/op
Client.createUser:createUser·p0.999   sample         14.637           ms/op
Client.createUser:createUser·p0.9999  sample         20.480           ms/op
Client.createUser:createUser·p1.00    sample         20.480           ms/op
Client.existUser                      sample  16339   1.957 ± 0.019   ms/op
Client.existUser:existUser·p0.00      sample          0.396           ms/op
Client.existUser:existUser·p0.50      sample          1.905           ms/op
Client.existUser:existUser·p0.90      sample          2.339           ms/op
Client.existUser:existUser·p0.95      sample          2.503           ms/op
Client.existUser:existUser·p0.99      sample          3.734           ms/op
Client.existUser:existUser·p0.999     sample         15.450           ms/op
Client.existUser:existUser·p0.9999    sample         15.593           ms/op
Client.existUser:existUser·p1.00      sample         15.614           ms/op
Client.getUser                        sample  10074   3.175 ± 0.024   ms/op
Client.getUser:getUser·p0.00          sample          0.787           ms/op
Client.getUser:getUser·p0.50          sample          3.154           ms/op
Client.getUser:getUser·p0.90          sample          4.084           ms/op
Client.getUser:getUser·p0.95          sample          4.342           ms/op
Client.getUser:getUser·p0.99          sample          5.014           ms/op
Client.getUser:getUser·p0.999         sample          6.798           ms/op
Client.getUser:getUser·p0.9999        sample          7.126           ms/op
Client.getUser:getUser·p1.00          sample          7.127           ms/op
Client.listUser                       sample   3661   8.742 ± 0.131   ms/op
Client.listUser:listUser·p0.00        sample          3.154           ms/op
Client.listUser:listUser·p0.50        sample          8.405           ms/op
Client.listUser:listUser·p0.90        sample         11.698           ms/op
Client.listUser:listUser·p0.95        sample         13.133           ms/op
Client.listUser:listUser·p0.99        sample         16.122           ms/op
Client.listUser:listUser·p0.999       sample         21.518           ms/op
Client.listUser:listUser·p0.9999      sample         24.052           ms/op
Client.listUser:listUser·p1.00        sample         24.052           ms/op
