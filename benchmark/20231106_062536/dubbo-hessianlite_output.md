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
# Warmup Iteration   1: 0.977 ops/ms
Iteration   1: 2.783 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.783 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:28
# Fork: 1 of 1
# Warmup Iteration   1: 2.642 ops/ms
Iteration   1: 6.145 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  6.145 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:19
# Fork: 1 of 1
# Warmup Iteration   1: 2.307 ops/ms
Iteration   1: 3.946 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.946 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:11
# Fork: 1 of 1
# Warmup Iteration   1: 0.872 ops/ms
Iteration   1: 1.391 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  1.391 ops/ms


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

# Run progress: 33.33% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 12.895 ±(99.9%) 0.279 ms/op
Iteration   1: 5.968 ±(99.9%) 0.060 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.968 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 8.906 ±(99.9%) 0.181 ms/op
Iteration   1: 3.346 ±(99.9%) 0.064 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  3.346 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:47
# Fork: 1 of 1
# Warmup Iteration   1: 11.549 ±(99.9%) 0.379 ms/op
Iteration   1: 4.953 ±(99.9%) 0.025 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  4.953 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:39
# Fork: 1 of 1
# Warmup Iteration   1: 34.135 ±(99.9%) 1.036 ms/op
Iteration   1: 26.100 ±(99.9%) 0.504 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  26.100 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:31
# Fork: 1 of 1
# Warmup Iteration   1: 10.491 ±(99.9%) 0.314 ms/op
Iteration   1: 5.396 ±(99.9%) 0.182 ms/op
                 createUser·p0.00:   1.317 ms/op
                 createUser·p0.50:   4.045 ms/op
                 createUser·p0.90:   8.862 ms/op
                 createUser·p0.95:   11.682 ms/op
                 createUser·p0.99:   22.654 ms/op
                 createUser·p0.999:  53.693 ms/op
                 createUser·p0.9999: 55.181 ms/op
                 createUser·p1.00:   55.181 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 5940
  mean =      5.396 ±(99.9%) 0.182 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 4041 
    [ 5.000, 10.000) = 1471 
    [10.000, 15.000) = 331 
    [15.000, 20.000) = 32 
    [20.000, 25.000) = 20 
    [25.000, 30.000) = 13 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 1 
    [40.000, 45.000) = 7 
    [45.000, 50.000) = 10 
    [50.000, 55.000) = 13 

  Percentiles, ms/op:
      p(0.0000) =      1.317 ms/op
     p(50.0000) =      4.045 ms/op
     p(90.0000) =      8.862 ms/op
     p(95.0000) =     11.682 ms/op
     p(99.0000) =     22.654 ms/op
     p(99.9000) =     53.693 ms/op
     p(99.9900) =     55.181 ms/op
     p(99.9990) =     55.181 ms/op
     p(99.9999) =     55.181 ms/op
    p(100.0000) =     55.181 ms/op


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

# Run progress: 75.00% complete, ETA 00:00:23
# Fork: 1 of 1
# Warmup Iteration   1: 8.081 ±(99.9%) 0.237 ms/op
Iteration   1: 2.925 ±(99.9%) 0.059 ms/op
                 existUser·p0.00:   0.777 ms/op
                 existUser·p0.50:   2.339 ms/op
                 existUser·p0.90:   4.084 ms/op
                 existUser·p0.95:   6.513 ms/op
                 existUser·p0.99:   11.190 ms/op
                 existUser·p0.999:  19.959 ms/op
                 existUser·p0.9999: 20.084 ms/op
                 existUser·p1.00:   20.087 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 10898
  mean =      2.925 ±(99.9%) 0.059 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6236 
    [ 2.500,  5.000) = 3980 
    [ 5.000,  7.500) = 300 
    [ 7.500, 10.000) = 197 
    [10.000, 12.500) = 96 
    [12.500, 15.000) = 39 
    [15.000, 17.500) = 18 
    [17.500, 20.000) = 27 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.777 ms/op
     p(50.0000) =      2.339 ms/op
     p(90.0000) =      4.084 ms/op
     p(95.0000) =      6.513 ms/op
     p(99.0000) =     11.190 ms/op
     p(99.9000) =     19.959 ms/op
     p(99.9900) =     20.084 ms/op
     p(99.9990) =     20.087 ms/op
     p(99.9999) =     20.087 ms/op
    p(100.0000) =     20.087 ms/op


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

# Run progress: 83.33% complete, ETA 00:00:15
# Fork: 1 of 1
# Warmup Iteration   1: 10.887 ±(99.9%) 0.350 ms/op
Iteration   1: 4.153 ±(99.9%) 0.076 ms/op
                 getUser·p0.00:   1.421 ms/op
                 getUser·p0.50:   3.637 ms/op
                 getUser·p0.90:   5.546 ms/op
                 getUser·p0.95:   6.873 ms/op
                 getUser·p0.99:   13.310 ms/op
                 getUser·p0.999:  21.726 ms/op
                 getUser·p0.9999: 25.362 ms/op
                 getUser·p1.00:   25.362 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 7781
  mean =      4.153 ±(99.9%) 0.076 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 134 
    [ 2.500,  5.000) = 6514 
    [ 5.000,  7.500) = 838 
    [ 7.500, 10.000) = 46 
    [10.000, 12.500) = 132 
    [12.500, 15.000) = 73 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 20 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.421 ms/op
     p(50.0000) =      3.637 ms/op
     p(90.0000) =      5.546 ms/op
     p(95.0000) =      6.873 ms/op
     p(99.0000) =     13.310 ms/op
     p(99.9000) =     21.726 ms/op
     p(99.9900) =     25.362 ms/op
     p(99.9990) =     25.362 ms/op
     p(99.9999) =     25.362 ms/op
    p(100.0000) =     25.362 ms/op


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
# Warmup Iteration   1: 29.699 ±(99.9%) 1.340 ms/op
Iteration   1: 23.230 ±(99.9%) 0.959 ms/op
                 listUser·p0.00:   1.894 ms/op
                 listUser·p0.50:   22.020 ms/op
                 listUser·p0.90:   32.050 ms/op
                 listUser·p0.95:   39.063 ms/op
                 listUser·p0.99:   51.617 ms/op
                 listUser·p0.999:  170.020 ms/op
                 listUser·p0.9999: 178.258 ms/op
                 listUser·p1.00:   178.258 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 1418
  mean =     23.230 ±(99.9%) 0.959 ms/op

  Histogram, ms/op:
    [  0.000,  12.500) = 80 
    [ 12.500,  25.000) = 855 
    [ 25.000,  37.500) = 406 
    [ 37.500,  50.000) = 61 
    [ 50.000,  62.500) = 8 
    [ 62.500,  75.000) = 1 
    [ 75.000,  87.500) = 1 
    [ 87.500, 100.000) = 1 
    [100.000, 112.500) = 1 
    [112.500, 125.000) = 0 
    [125.000, 137.500) = 2 
    [137.500, 150.000) = 0 
    [150.000, 162.500) = 1 
    [162.500, 175.000) = 0 
    [175.000, 187.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.894 ms/op
     p(50.0000) =     22.020 ms/op
     p(90.0000) =     32.050 ms/op
     p(95.0000) =     39.063 ms/op
     p(99.0000) =     51.617 ms/op
     p(99.9000) =    170.020 ms/op
     p(99.9900) =    178.258 ms/op
     p(99.9990) =    178.258 ms/op
     p(99.9999) =    178.258 ms/op
    p(100.0000) =    178.258 ms/op


# Run complete. Total time: 00:01:35

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt    Score   Error   Units
Client.createUser                      thrpt           2.783          ops/ms
Client.existUser                       thrpt           6.145          ops/ms
Client.getUser                         thrpt           3.946          ops/ms
Client.listUser                        thrpt           1.391          ops/ms
Client.createUser                       avgt           5.968           ms/op
Client.existUser                        avgt           3.346           ms/op
Client.getUser                          avgt           4.953           ms/op
Client.listUser                         avgt          26.100           ms/op
Client.createUser                     sample   5940    5.396 ± 0.182   ms/op
Client.createUser:createUser·p0.00    sample           1.317           ms/op
Client.createUser:createUser·p0.50    sample           4.045           ms/op
Client.createUser:createUser·p0.90    sample           8.862           ms/op
Client.createUser:createUser·p0.95    sample          11.682           ms/op
Client.createUser:createUser·p0.99    sample          22.654           ms/op
Client.createUser:createUser·p0.999   sample          53.693           ms/op
Client.createUser:createUser·p0.9999  sample          55.181           ms/op
Client.createUser:createUser·p1.00    sample          55.181           ms/op
Client.existUser                      sample  10898    2.925 ± 0.059   ms/op
Client.existUser:existUser·p0.00      sample           0.777           ms/op
Client.existUser:existUser·p0.50      sample           2.339           ms/op
Client.existUser:existUser·p0.90      sample           4.084           ms/op
Client.existUser:existUser·p0.95      sample           6.513           ms/op
Client.existUser:existUser·p0.99      sample          11.190           ms/op
Client.existUser:existUser·p0.999     sample          19.959           ms/op
Client.existUser:existUser·p0.9999    sample          20.084           ms/op
Client.existUser:existUser·p1.00      sample          20.087           ms/op
Client.getUser                        sample   7781    4.153 ± 0.076   ms/op
Client.getUser:getUser·p0.00          sample           1.421           ms/op
Client.getUser:getUser·p0.50          sample           3.637           ms/op
Client.getUser:getUser·p0.90          sample           5.546           ms/op
Client.getUser:getUser·p0.95          sample           6.873           ms/op
Client.getUser:getUser·p0.99          sample          13.310           ms/op
Client.getUser:getUser·p0.999         sample          21.726           ms/op
Client.getUser:getUser·p0.9999        sample          25.362           ms/op
Client.getUser:getUser·p1.00          sample          25.362           ms/op
Client.listUser                       sample   1418   23.230 ± 0.959   ms/op
Client.listUser:listUser·p0.00        sample           1.894           ms/op
Client.listUser:listUser·p0.50        sample          22.020           ms/op
Client.listUser:listUser·p0.90        sample          32.050           ms/op
Client.listUser:listUser·p0.95        sample          39.063           ms/op
Client.listUser:listUser·p0.99        sample          51.617           ms/op
Client.listUser:listUser·p0.999       sample         170.020           ms/op
Client.listUser:listUser·p0.9999      sample         178.258           ms/op
Client.listUser:listUser·p1.00        sample         178.258           ms/op
