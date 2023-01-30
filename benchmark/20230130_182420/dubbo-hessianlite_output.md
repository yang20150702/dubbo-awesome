# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 1.069 ops/ms
Iteration   1: 2.020 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.020 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 8.33% complete, ETA 00:01:19
# Fork: 1 of 1
# Warmup Iteration   1: 2.132 ops/ms
Iteration   1: 3.894 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  3.894 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 16.67% complete, ETA 00:01:12
# Fork: 1 of 1
# Warmup Iteration   1: 1.645 ops/ms
Iteration   1: 3.905 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.905 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 25.00% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 0.945 ops/ms
Iteration   1: 1.242 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  1.242 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 33.33% complete, ETA 00:00:57
# Fork: 1 of 1
# Warmup Iteration   1: 19.828 ±(99.9%) 0.339 ms/op
Iteration   1: 10.658 ±(99.9%) 0.041 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  10.658 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 41.67% complete, ETA 00:00:50
# Fork: 1 of 1
# Warmup Iteration   1: 9.924 ±(99.9%) 0.155 ms/op
Iteration   1: 5.257 ±(99.9%) 0.026 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  5.257 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 50.00% complete, ETA 00:00:43
# Fork: 1 of 1
# Warmup Iteration   1: 15.458 ±(99.9%) 0.213 ms/op
Iteration   1: 5.330 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  5.330 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 31.669 ±(99.9%) 0.428 ms/op
Iteration   1: 21.984 ±(99.9%) 0.058 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  21.984 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 14.547 ±(99.9%) 0.552 ms/op
Iteration   1: 7.116 ±(99.9%) 0.158 ms/op
                 createUser·p0.00:   1.864 ms/op
                 createUser·p0.50:   8.372 ms/op
                 createUser·p0.90:   9.617 ms/op
                 createUser·p0.95:   10.273 ms/op
                 createUser·p0.99:   19.824 ms/op
                 createUser·p0.999:  22.642 ms/op
                 createUser·p0.9999: 23.003 ms/op
                 createUser·p1.00:   23.003 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 4502
  mean =      7.116 ±(99.9%) 0.158 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 73 
    [ 2.500,  5.000) = 1473 
    [ 5.000,  7.500) = 531 
    [ 7.500, 10.000) = 2156 
    [10.000, 12.500) = 136 
    [12.500, 15.000) = 49 
    [15.000, 17.500) = 20 
    [17.500, 20.000) = 43 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.864 ms/op
     p(50.0000) =      8.372 ms/op
     p(90.0000) =      9.617 ms/op
     p(95.0000) =     10.273 ms/op
     p(99.0000) =     19.824 ms/op
     p(99.9000) =     22.642 ms/op
     p(99.9900) =     23.003 ms/op
     p(99.9990) =     23.003 ms/op
     p(99.9999) =     23.003 ms/op
    p(100.0000) =     23.003 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 8.975 ±(99.9%) 0.258 ms/op
Iteration   1: 4.356 ±(99.9%) 0.079 ms/op
                 existUser·p0.00:   0.822 ms/op
                 existUser·p0.50:   4.166 ms/op
                 existUser·p0.90:   4.719 ms/op
                 existUser·p0.95:   5.847 ms/op
                 existUser·p0.99:   12.288 ms/op
                 existUser·p0.999:  25.402 ms/op
                 existUser·p0.9999: 25.723 ms/op
                 existUser·p1.00:   25.723 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 7391
  mean =      4.356 ±(99.9%) 0.079 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 218 
    [ 2.500,  5.000) = 6651 
    [ 5.000,  7.500) = 216 
    [ 7.500, 10.000) = 51 
    [10.000, 12.500) = 182 
    [12.500, 15.000) = 39 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 15 

  Percentiles, ms/op:
      p(0.0000) =      0.822 ms/op
     p(50.0000) =      4.166 ms/op
     p(90.0000) =      4.719 ms/op
     p(95.0000) =      5.847 ms/op
     p(99.0000) =     12.288 ms/op
     p(99.9000) =     25.402 ms/op
     p(99.9900) =     25.723 ms/op
     p(99.9990) =     25.723 ms/op
     p(99.9999) =     25.723 ms/op
    p(100.0000) =     25.723 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 12.582 ±(99.9%) 0.411 ms/op
Iteration   1: 5.003 ±(99.9%) 0.079 ms/op
                 getUser·p0.00:   1.575 ms/op
                 getUser·p0.50:   4.637 ms/op
                 getUser·p0.90:   6.091 ms/op
                 getUser·p0.95:   7.139 ms/op
                 getUser·p0.99:   14.857 ms/op
                 getUser·p0.999:  24.383 ms/op
                 getUser·p0.9999: 24.773 ms/op
                 getUser·p1.00:   24.773 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 6444
  mean =      5.003 ±(99.9%) 0.079 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 43 
    [ 2.500,  5.000) = 4308 
    [ 5.000,  7.500) = 1849 
    [ 7.500, 10.000) = 141 
    [10.000, 12.500) = 27 
    [12.500, 15.000) = 12 
    [15.000, 17.500) = 21 
    [17.500, 20.000) = 11 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.575 ms/op
     p(50.0000) =      4.637 ms/op
     p(90.0000) =      6.091 ms/op
     p(95.0000) =      7.139 ms/op
     p(99.0000) =     14.857 ms/op
     p(99.9000) =     24.383 ms/op
     p(99.9900) =     24.773 ms/op
     p(99.9990) =     24.773 ms/op
     p(99.9999) =     24.773 ms/op
    p(100.0000) =     24.773 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 28.302 ±(99.9%) 0.832 ms/op
Iteration   1: 20.311 ±(99.9%) 0.307 ms/op
                 listUser·p0.00:   6.283 ms/op
                 listUser·p0.50:   20.447 ms/op
                 listUser·p0.90:   24.193 ms/op
                 listUser·p0.95:   26.975 ms/op
                 listUser·p0.99:   31.036 ms/op
                 listUser·p0.999:  34.319 ms/op
                 listUser·p0.9999: 35.127 ms/op
                 listUser·p1.00:   35.127 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 1586
  mean =     20.311 ±(99.9%) 0.307 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 0 
    [ 5.000,  7.500) = 6 
    [ 7.500, 10.000) = 22 
    [10.000, 12.500) = 36 
    [12.500, 15.000) = 88 
    [15.000, 17.500) = 53 
    [17.500, 20.000) = 444 
    [20.000, 22.500) = 736 
    [22.500, 25.000) = 86 
    [25.000, 27.500) = 45 
    [27.500, 30.000) = 35 
    [30.000, 32.500) = 33 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      6.283 ms/op
     p(50.0000) =     20.447 ms/op
     p(90.0000) =     24.193 ms/op
     p(95.0000) =     26.975 ms/op
     p(99.0000) =     31.036 ms/op
     p(99.9000) =     34.319 ms/op
     p(99.9900) =     35.127 ms/op
     p(99.9990) =     35.127 ms/op
     p(99.9999) =     35.127 ms/op
    p(100.0000) =     35.127 ms/op


# Run complete. Total time: 00:01:26

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode   Cnt   Score   Error   Units
Client.createUser                      thrpt         2.020          ops/ms
Client.existUser                       thrpt         3.894          ops/ms
Client.getUser                         thrpt         3.905          ops/ms
Client.listUser                        thrpt         1.242          ops/ms
Client.createUser                       avgt        10.658           ms/op
Client.existUser                        avgt         5.257           ms/op
Client.getUser                          avgt         5.330           ms/op
Client.listUser                         avgt        21.984           ms/op
Client.createUser                     sample  4502   7.116 ± 0.158   ms/op
Client.createUser:createUser·p0.00    sample         1.864           ms/op
Client.createUser:createUser·p0.50    sample         8.372           ms/op
Client.createUser:createUser·p0.90    sample         9.617           ms/op
Client.createUser:createUser·p0.95    sample        10.273           ms/op
Client.createUser:createUser·p0.99    sample        19.824           ms/op
Client.createUser:createUser·p0.999   sample        22.642           ms/op
Client.createUser:createUser·p0.9999  sample        23.003           ms/op
Client.createUser:createUser·p1.00    sample        23.003           ms/op
Client.existUser                      sample  7391   4.356 ± 0.079   ms/op
Client.existUser:existUser·p0.00      sample         0.822           ms/op
Client.existUser:existUser·p0.50      sample         4.166           ms/op
Client.existUser:existUser·p0.90      sample         4.719           ms/op
Client.existUser:existUser·p0.95      sample         5.847           ms/op
Client.existUser:existUser·p0.99      sample        12.288           ms/op
Client.existUser:existUser·p0.999     sample        25.402           ms/op
Client.existUser:existUser·p0.9999    sample        25.723           ms/op
Client.existUser:existUser·p1.00      sample        25.723           ms/op
Client.getUser                        sample  6444   5.003 ± 0.079   ms/op
Client.getUser:getUser·p0.00          sample         1.575           ms/op
Client.getUser:getUser·p0.50          sample         4.637           ms/op
Client.getUser:getUser·p0.90          sample         6.091           ms/op
Client.getUser:getUser·p0.95          sample         7.139           ms/op
Client.getUser:getUser·p0.99          sample        14.857           ms/op
Client.getUser:getUser·p0.999         sample        24.383           ms/op
Client.getUser:getUser·p0.9999        sample        24.773           ms/op
Client.getUser:getUser·p1.00          sample        24.773           ms/op
Client.listUser                       sample  1586  20.311 ± 0.307   ms/op
Client.listUser:listUser·p0.00        sample         6.283           ms/op
Client.listUser:listUser·p0.50        sample        20.447           ms/op
Client.listUser:listUser·p0.90        sample        24.193           ms/op
Client.listUser:listUser·p0.95        sample        26.975           ms/op
Client.listUser:listUser·p0.99        sample        31.036           ms/op
Client.listUser:listUser·p0.999       sample        34.319           ms/op
Client.listUser:listUser·p0.9999      sample        35.127           ms/op
Client.listUser:listUser·p1.00        sample        35.127           ms/op
