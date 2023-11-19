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
# Warmup Iteration   1: 2.240 ops/ms
Iteration   1: 5.805 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.805 ops/ms


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
# Warmup Iteration   1: 7.945 ops/ms
Iteration   1: 13.645 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  13.645 ops/ms


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
# Warmup Iteration   1: 4.189 ops/ms
Iteration   1: 8.770 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.770 ops/ms


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
# Warmup Iteration   1: 2.241 ops/ms
Iteration   1: 4.373 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  4.373 ops/ms


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
# Warmup Iteration   1: 5.139 ±(99.9%) 0.055 ms/op
Iteration   1: 2.962 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.962 ms/op


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
# Warmup Iteration   1: 2.989 ±(99.9%) 0.029 ms/op
Iteration   1: 2.042 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  2.042 ms/op


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
# Warmup Iteration   1: 4.919 ±(99.9%) 0.075 ms/op
Iteration   1: 2.799 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  2.799 ms/op


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
# Warmup Iteration   1: 11.705 ±(99.9%) 0.231 ms/op
Iteration   1: 7.655 ±(99.9%) 0.073 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  7.655 ms/op


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
# Warmup Iteration   1: 4.680 ±(99.9%) 0.092 ms/op
Iteration   1: 3.153 ±(99.9%) 0.040 ms/op
                 createUser·p0.00:   1.425 ms/op
                 createUser·p0.50:   2.863 ms/op
                 createUser·p0.90:   3.870 ms/op
                 createUser·p0.95:   4.334 ms/op
                 createUser·p0.99:   8.311 ms/op
                 createUser·p0.999:  15.094 ms/op
                 createUser·p0.9999: 16.687 ms/op
                 createUser·p1.00:   16.695 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10351
  mean =      3.153 ±(99.9%) 0.040 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 1037 
    [ 2.500,  3.750) = 8077 
    [ 3.750,  5.000) = 920 
    [ 5.000,  6.250) = 121 
    [ 6.250,  7.500) = 61 
    [ 7.500,  8.750) = 35 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 3 
    [11.250, 12.500) = 23 
    [12.500, 13.750) = 39 
    [13.750, 15.000) = 20 
    [15.000, 16.250) = 12 
    [16.250, 17.500) = 2 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.425 ms/op
     p(50.0000) =      2.863 ms/op
     p(90.0000) =      3.870 ms/op
     p(95.0000) =      4.334 ms/op
     p(99.0000) =      8.311 ms/op
     p(99.9000) =     15.094 ms/op
     p(99.9900) =     16.687 ms/op
     p(99.9990) =     16.695 ms/op
     p(99.9999) =     16.695 ms/op
    p(100.0000) =     16.695 ms/op


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
# Warmup Iteration   1: 3.004 ±(99.9%) 0.063 ms/op
Iteration   1: 2.157 ±(99.9%) 0.088 ms/op
                 existUser·p0.00:   0.574 ms/op
                 existUser·p0.50:   1.872 ms/op
                 existUser·p0.90:   2.564 ms/op
                 existUser·p0.95:   2.781 ms/op
                 existUser·p0.99:   4.809 ms/op
                 existUser·p0.999:  69.001 ms/op
                 existUser·p0.9999: 85.983 ms/op
                 existUser·p1.00:   85.983 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 14818
  mean =      2.157 ±(99.9%) 0.088 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 14696 
    [ 5.000, 10.000) = 69 
    [10.000, 15.000) = 3 
    [15.000, 20.000) = 3 
    [20.000, 25.000) = 6 
    [25.000, 30.000) = 2 
    [30.000, 35.000) = 1 
    [35.000, 40.000) = 2 
    [40.000, 45.000) = 7 
    [45.000, 50.000) = 3 
    [50.000, 55.000) = 2 
    [55.000, 60.000) = 2 
    [60.000, 65.000) = 5 
    [65.000, 70.000) = 3 
    [70.000, 75.000) = 5 
    [75.000, 80.000) = 4 
    [80.000, 85.000) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.574 ms/op
     p(50.0000) =      1.872 ms/op
     p(90.0000) =      2.564 ms/op
     p(95.0000) =      2.781 ms/op
     p(99.0000) =      4.809 ms/op
     p(99.9000) =     69.001 ms/op
     p(99.9900) =     85.983 ms/op
     p(99.9990) =     85.983 ms/op
     p(99.9999) =     85.983 ms/op
    p(100.0000) =     85.983 ms/op


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
# Warmup Iteration   1: 4.265 ±(99.9%) 0.081 ms/op
Iteration   1: 2.834 ±(99.9%) 0.027 ms/op
                 getUser·p0.00:   0.734 ms/op
                 getUser·p0.50:   2.765 ms/op
                 getUser·p0.90:   3.490 ms/op
                 getUser·p0.95:   3.772 ms/op
                 getUser·p0.99:   5.014 ms/op
                 getUser·p0.999:  15.228 ms/op
                 getUser·p0.9999: 15.841 ms/op
                 getUser·p1.00:   15.860 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 11289
  mean =      2.834 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 26 
    [ 1.250,  2.500) = 3662 
    [ 2.500,  3.750) = 7006 
    [ 3.750,  5.000) = 482 
    [ 5.000,  6.250) = 76 
    [ 6.250,  7.500) = 2 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 13 
    [15.000, 16.250) = 19 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.734 ms/op
     p(50.0000) =      2.765 ms/op
     p(90.0000) =      3.490 ms/op
     p(95.0000) =      3.772 ms/op
     p(99.0000) =      5.014 ms/op
     p(99.9000) =     15.228 ms/op
     p(99.9900) =     15.841 ms/op
     p(99.9990) =     15.860 ms/op
     p(99.9999) =     15.860 ms/op
    p(100.0000) =     15.860 ms/op


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
# Warmup Iteration   1: 10.932 ±(99.9%) 0.333 ms/op
Iteration   1: 6.676 ±(99.9%) 0.091 ms/op
                 listUser·p0.00:   2.540 ms/op
                 listUser·p0.50:   6.414 ms/op
                 listUser·p0.90:   8.503 ms/op
                 listUser·p0.95:   9.421 ms/op
                 listUser·p0.99:   15.679 ms/op
                 listUser·p0.999:  19.962 ms/op
                 listUser·p0.9999: 21.561 ms/op
                 listUser·p1.00:   21.561 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 4792
  mean =      6.676 ±(99.9%) 0.091 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 557 
    [ 5.000,  7.500) = 3165 
    [ 7.500, 10.000) = 892 
    [10.000, 12.500) = 88 
    [12.500, 15.000) = 30 
    [15.000, 17.500) = 35 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.540 ms/op
     p(50.0000) =      6.414 ms/op
     p(90.0000) =      8.503 ms/op
     p(95.0000) =      9.421 ms/op
     p(99.0000) =     15.679 ms/op
     p(99.9000) =     19.962 ms/op
     p(99.9900) =     21.561 ms/op
     p(99.9990) =     21.561 ms/op
     p(99.9999) =     21.561 ms/op
    p(100.0000) =     21.561 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.805          ops/ms
Client.existUser                       thrpt         13.645          ops/ms
Client.getUser                         thrpt          8.770          ops/ms
Client.listUser                        thrpt          4.373          ops/ms
Client.createUser                       avgt          2.962           ms/op
Client.existUser                        avgt          2.042           ms/op
Client.getUser                          avgt          2.799           ms/op
Client.listUser                         avgt          7.655           ms/op
Client.createUser                     sample  10351   3.153 ± 0.040   ms/op
Client.createUser:createUser·p0.00    sample          1.425           ms/op
Client.createUser:createUser·p0.50    sample          2.863           ms/op
Client.createUser:createUser·p0.90    sample          3.870           ms/op
Client.createUser:createUser·p0.95    sample          4.334           ms/op
Client.createUser:createUser·p0.99    sample          8.311           ms/op
Client.createUser:createUser·p0.999   sample         15.094           ms/op
Client.createUser:createUser·p0.9999  sample         16.687           ms/op
Client.createUser:createUser·p1.00    sample         16.695           ms/op
Client.existUser                      sample  14818   2.157 ± 0.088   ms/op
Client.existUser:existUser·p0.00      sample          0.574           ms/op
Client.existUser:existUser·p0.50      sample          1.872           ms/op
Client.existUser:existUser·p0.90      sample          2.564           ms/op
Client.existUser:existUser·p0.95      sample          2.781           ms/op
Client.existUser:existUser·p0.99      sample          4.809           ms/op
Client.existUser:existUser·p0.999     sample         69.001           ms/op
Client.existUser:existUser·p0.9999    sample         85.983           ms/op
Client.existUser:existUser·p1.00      sample         85.983           ms/op
Client.getUser                        sample  11289   2.834 ± 0.027   ms/op
Client.getUser:getUser·p0.00          sample          0.734           ms/op
Client.getUser:getUser·p0.50          sample          2.765           ms/op
Client.getUser:getUser·p0.90          sample          3.490           ms/op
Client.getUser:getUser·p0.95          sample          3.772           ms/op
Client.getUser:getUser·p0.99          sample          5.014           ms/op
Client.getUser:getUser·p0.999         sample         15.228           ms/op
Client.getUser:getUser·p0.9999        sample         15.841           ms/op
Client.getUser:getUser·p1.00          sample         15.860           ms/op
Client.listUser                       sample   4792   6.676 ± 0.091   ms/op
Client.listUser:listUser·p0.00        sample          2.540           ms/op
Client.listUser:listUser·p0.50        sample          6.414           ms/op
Client.listUser:listUser·p0.90        sample          8.503           ms/op
Client.listUser:listUser·p0.95        sample          9.421           ms/op
Client.listUser:listUser·p0.99        sample         15.679           ms/op
Client.listUser:listUser·p0.999       sample         19.962           ms/op
Client.listUser:listUser·p0.9999      sample         21.561           ms/op
Client.listUser:listUser·p1.00        sample         21.561           ms/op
