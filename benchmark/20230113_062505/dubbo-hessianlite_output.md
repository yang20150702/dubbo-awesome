# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 0.850 ops/ms
Iteration   1: 1.979 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  1.979 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 8.33% complete, ETA 00:01:22
# Fork: 1 of 1
# Warmup Iteration   1: 2.389 ops/ms
Iteration   1: 4.658 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  4.658 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 16.67% complete, ETA 00:01:13
# Fork: 1 of 1
# Warmup Iteration   1: 1.887 ops/ms
Iteration   1: 3.691 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.691 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 25.00% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 0.637 ops/ms
Iteration   1: 1.112 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  1.112 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 33.33% complete, ETA 00:00:59
# Fork: 1 of 1
# Warmup Iteration   1: 20.797 ±(99.9%) 0.354 ms/op
Iteration   1: 11.339 ±(99.9%) 0.045 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  11.339 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 41.67% complete, ETA 00:00:51
# Fork: 1 of 1
# Warmup Iteration   1: 14.495 ±(99.9%) 0.204 ms/op
Iteration   1: 7.024 ±(99.9%) 0.023 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  7.024 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 50.00% complete, ETA 00:00:44
# Fork: 1 of 1
# Warmup Iteration   1: 15.304 ±(99.9%) 0.290 ms/op
Iteration   1: 5.982 ±(99.9%) 0.055 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  5.982 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 58.33% complete, ETA 00:00:36
# Fork: 1 of 1
# Warmup Iteration   1: 35.061 ±(99.9%) 1.114 ms/op
Iteration   1: 24.955 ±(99.9%) 0.179 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  24.955 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 66.67% complete, ETA 00:00:29
# Fork: 1 of 1
# Warmup Iteration   1: 16.825 ±(99.9%) 0.456 ms/op
Iteration   1: 7.879 ±(99.9%) 0.191 ms/op
                 createUser·p0.00:   2.576 ms/op
                 createUser·p0.50:   7.102 ms/op
                 createUser·p0.90:   10.381 ms/op
                 createUser·p0.95:   14.929 ms/op
                 createUser·p0.99:   21.209 ms/op
                 createUser·p0.999:  31.094 ms/op
                 createUser·p0.9999: 31.490 ms/op
                 createUser·p1.00:   31.490 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 4073
  mean =      7.879 ±(99.9%) 0.191 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 669 
    [ 5.000,  7.500) = 1872 
    [ 7.500, 10.000) = 1082 
    [10.000, 12.500) = 124 
    [12.500, 15.000) = 125 
    [15.000, 17.500) = 75 
    [17.500, 20.000) = 33 
    [20.000, 22.500) = 61 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 16 
    [30.000, 32.500) = 16 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.576 ms/op
     p(50.0000) =      7.102 ms/op
     p(90.0000) =     10.381 ms/op
     p(95.0000) =     14.929 ms/op
     p(99.0000) =     21.209 ms/op
     p(99.9000) =     31.094 ms/op
     p(99.9900) =     31.490 ms/op
     p(99.9990) =     31.490 ms/op
     p(99.9999) =     31.490 ms/op
    p(100.0000) =     31.490 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 75.00% complete, ETA 00:00:22
# Fork: 1 of 1
# Warmup Iteration   1: 10.403 ±(99.9%) 0.380 ms/op
Iteration   1: 6.920 ±(99.9%) 0.153 ms/op
                 existUser·p0.00:   0.390 ms/op
                 existUser·p0.50:   6.701 ms/op
                 existUser·p0.90:   10.011 ms/op
                 existUser·p0.95:   13.926 ms/op
                 existUser·p0.99:   16.938 ms/op
                 existUser·p0.999:  29.034 ms/op
                 existUser·p0.9999: 29.131 ms/op
                 existUser·p1.00:   29.131 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 4654
  mean =      6.920 ±(99.9%) 0.153 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15 
    [ 2.500,  5.000) = 1222 
    [ 5.000,  7.500) = 2376 
    [ 7.500, 10.000) = 573 
    [10.000, 12.500) = 155 
    [12.500, 15.000) = 175 
    [15.000, 17.500) = 106 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.390 ms/op
     p(50.0000) =      6.701 ms/op
     p(90.0000) =     10.011 ms/op
     p(95.0000) =     13.926 ms/op
     p(99.0000) =     16.938 ms/op
     p(99.9000) =     29.034 ms/op
     p(99.9900) =     29.131 ms/op
     p(99.9990) =     29.131 ms/op
     p(99.9999) =     29.131 ms/op
    p(100.0000) =     29.131 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 12.944 ±(99.9%) 0.464 ms/op
Iteration   1: 6.349 ±(99.9%) 0.169 ms/op
                 getUser·p0.00:   2.236 ms/op
                 getUser·p0.50:   5.464 ms/op
                 getUser·p0.90:   8.700 ms/op
                 getUser·p0.95:   11.305 ms/op
                 getUser·p0.99:   24.642 ms/op
                 getUser·p0.999:  45.090 ms/op
                 getUser·p0.9999: 45.613 ms/op
                 getUser·p1.00:   45.613 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 4979
  mean =      6.349 ±(99.9%) 0.169 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 800 
    [ 5.000, 10.000) = 3890 
    [10.000, 15.000) = 198 
    [15.000, 20.000) = 36 
    [20.000, 25.000) = 19 
    [25.000, 30.000) = 13 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 16 

  Percentiles, ms/op:
      p(0.0000) =      2.236 ms/op
     p(50.0000) =      5.464 ms/op
     p(90.0000) =      8.700 ms/op
     p(95.0000) =     11.305 ms/op
     p(99.0000) =     24.642 ms/op
     p(99.9000) =     45.090 ms/op
     p(99.9900) =     45.613 ms/op
     p(99.9990) =     45.613 ms/op
     p(99.9999) =     45.613 ms/op
    p(100.0000) =     45.613 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 32.096 ±(99.9%) 1.183 ms/op
Iteration   1: 23.889 ±(99.9%) 0.502 ms/op
                 listUser·p0.00:   7.873 ms/op
                 listUser·p0.50:   22.938 ms/op
                 listUser·p0.90:   29.878 ms/op
                 listUser·p0.95:   34.859 ms/op
                 listUser·p0.99:   45.389 ms/op
                 listUser·p0.999:  58.048 ms/op
                 listUser·p0.9999: 60.424 ms/op
                 listUser·p1.00:   60.424 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 1341
  mean =     23.889 ±(99.9%) 0.502 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 0 
    [ 5.000, 10.000) = 12 
    [10.000, 15.000) = 6 
    [15.000, 20.000) = 243 
    [20.000, 25.000) = 741 
    [25.000, 30.000) = 209 
    [30.000, 35.000) = 65 
    [35.000, 40.000) = 38 
    [40.000, 45.000) = 9 
    [45.000, 50.000) = 13 
    [50.000, 55.000) = 4 
    [55.000, 60.000) = 0 
    [60.000, 65.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      7.873 ms/op
     p(50.0000) =     22.938 ms/op
     p(90.0000) =     29.878 ms/op
     p(95.0000) =     34.859 ms/op
     p(99.0000) =     45.389 ms/op
     p(99.9000) =     58.048 ms/op
     p(99.9900) =     60.424 ms/op
     p(99.9990) =     60.424 ms/op
     p(99.9999) =     60.424 ms/op
    p(100.0000) =     60.424 ms/op


# Run complete. Total time: 00:01:29

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode   Cnt   Score   Error   Units
Client.createUser                      thrpt         1.979          ops/ms
Client.existUser                       thrpt         4.658          ops/ms
Client.getUser                         thrpt         3.691          ops/ms
Client.listUser                        thrpt         1.112          ops/ms
Client.createUser                       avgt        11.339           ms/op
Client.existUser                        avgt         7.024           ms/op
Client.getUser                          avgt         5.982           ms/op
Client.listUser                         avgt        24.955           ms/op
Client.createUser                     sample  4073   7.879 ± 0.191   ms/op
Client.createUser:createUser·p0.00    sample         2.576           ms/op
Client.createUser:createUser·p0.50    sample         7.102           ms/op
Client.createUser:createUser·p0.90    sample        10.381           ms/op
Client.createUser:createUser·p0.95    sample        14.929           ms/op
Client.createUser:createUser·p0.99    sample        21.209           ms/op
Client.createUser:createUser·p0.999   sample        31.094           ms/op
Client.createUser:createUser·p0.9999  sample        31.490           ms/op
Client.createUser:createUser·p1.00    sample        31.490           ms/op
Client.existUser                      sample  4654   6.920 ± 0.153   ms/op
Client.existUser:existUser·p0.00      sample         0.390           ms/op
Client.existUser:existUser·p0.50      sample         6.701           ms/op
Client.existUser:existUser·p0.90      sample        10.011           ms/op
Client.existUser:existUser·p0.95      sample        13.926           ms/op
Client.existUser:existUser·p0.99      sample        16.938           ms/op
Client.existUser:existUser·p0.999     sample        29.034           ms/op
Client.existUser:existUser·p0.9999    sample        29.131           ms/op
Client.existUser:existUser·p1.00      sample        29.131           ms/op
Client.getUser                        sample  4979   6.349 ± 0.169   ms/op
Client.getUser:getUser·p0.00          sample         2.236           ms/op
Client.getUser:getUser·p0.50          sample         5.464           ms/op
Client.getUser:getUser·p0.90          sample         8.700           ms/op
Client.getUser:getUser·p0.95          sample        11.305           ms/op
Client.getUser:getUser·p0.99          sample        24.642           ms/op
Client.getUser:getUser·p0.999         sample        45.090           ms/op
Client.getUser:getUser·p0.9999        sample        45.613           ms/op
Client.getUser:getUser·p1.00          sample        45.613           ms/op
Client.listUser                       sample  1341  23.889 ± 0.502   ms/op
Client.listUser:listUser·p0.00        sample         7.873           ms/op
Client.listUser:listUser·p0.50        sample        22.938           ms/op
Client.listUser:listUser·p0.90        sample        29.878           ms/op
Client.listUser:listUser·p0.95        sample        34.859           ms/op
Client.listUser:listUser·p0.99        sample        45.389           ms/op
Client.listUser:listUser·p0.999       sample        58.048           ms/op
Client.listUser:listUser·p0.9999      sample        60.424           ms/op
Client.listUser:listUser·p1.00        sample        60.424           ms/op
