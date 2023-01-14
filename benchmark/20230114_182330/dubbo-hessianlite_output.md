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
# Warmup Iteration   1: 1.003 ops/ms
Iteration   1: 2.379 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.379 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:19
# Fork: 1 of 1
# Warmup Iteration   1: 2.123 ops/ms
Iteration   1: 7.154 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  7.154 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 2.185 ops/ms
Iteration   1: 4.603 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  4.603 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 0.917 ops/ms
Iteration   1: 1.249 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  1.249 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 17.441 ±(99.9%) 0.218 ms/op
Iteration   1: 8.537 ±(99.9%) 0.025 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  8.537 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 6.583 ±(99.9%) 0.076 ms/op
Iteration   1: 4.744 ±(99.9%) 0.028 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  4.744 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 10.810 ±(99.9%) 0.140 ms/op
Iteration   1: 5.377 ±(99.9%) 0.038 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  5.377 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 29.335 ±(99.9%) 0.833 ms/op
Iteration   1: 19.290 ±(99.9%) 0.108 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  19.290 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 13.540 ±(99.9%) 0.561 ms/op
Iteration   1: 8.507 ±(99.9%) 0.183 ms/op
                 createUser·p0.00:   1.651 ms/op
                 createUser·p0.50:   7.889 ms/op
                 createUser·p0.90:   9.339 ms/op
                 createUser·p0.95:   13.603 ms/op
                 createUser·p0.99:   16.843 ms/op
                 createUser·p0.999:  40.517 ms/op
                 createUser·p0.9999: 40.698 ms/op
                 createUser·p1.00:   40.698 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 3754
  mean =      8.507 ±(99.9%) 0.183 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 87 
    [ 5.000, 10.000) = 3342 
    [10.000, 15.000) = 203 
    [15.000, 20.000) = 90 
    [20.000, 25.000) = 0 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 26 
    [40.000, 45.000) = 6 

  Percentiles, ms/op:
      p(0.0000) =      1.651 ms/op
     p(50.0000) =      7.889 ms/op
     p(90.0000) =      9.339 ms/op
     p(95.0000) =     13.603 ms/op
     p(99.0000) =     16.843 ms/op
     p(99.9000) =     40.517 ms/op
     p(99.9900) =     40.698 ms/op
     p(99.9990) =     40.698 ms/op
     p(99.9999) =     40.698 ms/op
    p(100.0000) =     40.698 ms/op


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

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 7.164 ±(99.9%) 0.216 ms/op
Iteration   1: 4.740 ±(99.9%) 0.060 ms/op
                 existUser·p0.00:   1.327 ms/op
                 existUser·p0.50:   4.620 ms/op
                 existUser·p0.90:   5.104 ms/op
                 existUser·p0.95:   5.382 ms/op
                 existUser·p0.99:   12.681 ms/op
                 existUser·p0.999:  13.304 ms/op
                 existUser·p0.9999: 14.139 ms/op
                 existUser·p1.00:   14.139 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 6759
  mean =      4.740 ±(99.9%) 0.060 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 196 
    [ 2.500,  3.750) = 182 
    [ 3.750,  5.000) = 5239 
    [ 5.000,  6.250) = 847 
    [ 6.250,  7.500) = 68 
    [ 7.500,  8.750) = 3 
    [ 8.750, 10.000) = 6 
    [10.000, 11.250) = 66 
    [11.250, 12.500) = 78 
    [12.500, 13.750) = 71 
    [13.750, 15.000) = 3 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.327 ms/op
     p(50.0000) =      4.620 ms/op
     p(90.0000) =      5.104 ms/op
     p(95.0000) =      5.382 ms/op
     p(99.0000) =     12.681 ms/op
     p(99.9000) =     13.304 ms/op
     p(99.9900) =     14.139 ms/op
     p(99.9990) =     14.139 ms/op
     p(99.9999) =     14.139 ms/op
    p(100.0000) =     14.139 ms/op


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
# Warmup Iteration   1: 14.165 ±(99.9%) 0.382 ms/op
Iteration   1: 4.889 ±(99.9%) 0.090 ms/op
                 getUser·p0.00:   2.236 ms/op
                 getUser·p0.50:   4.555 ms/op
                 getUser·p0.90:   5.186 ms/op
                 getUser·p0.95:   6.218 ms/op
                 getUser·p0.99:   14.189 ms/op
                 getUser·p0.999:  31.228 ms/op
                 getUser·p0.9999: 31.326 ms/op
                 getUser·p1.00:   31.326 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 6634
  mean =      4.889 ±(99.9%) 0.090 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4 
    [ 2.500,  5.000) = 5658 
    [ 5.000,  7.500) = 767 
    [ 7.500, 10.000) = 107 
    [10.000, 12.500) = 2 
    [12.500, 15.000) = 33 
    [15.000, 17.500) = 27 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 32 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.236 ms/op
     p(50.0000) =      4.555 ms/op
     p(90.0000) =      5.186 ms/op
     p(95.0000) =      6.218 ms/op
     p(99.0000) =     14.189 ms/op
     p(99.9000) =     31.228 ms/op
     p(99.9900) =     31.326 ms/op
     p(99.9990) =     31.326 ms/op
     p(99.9999) =     31.326 ms/op
    p(100.0000) =     31.326 ms/op


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
# Warmup Iteration   1: 27.571 ±(99.9%) 0.948 ms/op
Iteration   1: 16.769 ±(99.9%) 0.312 ms/op
                 listUser·p0.00:   2.998 ms/op
                 listUser·p0.50:   15.598 ms/op
                 listUser·p0.90:   22.577 ms/op
                 listUser·p0.95:   23.331 ms/op
                 listUser·p0.99:   26.378 ms/op
                 listUser·p0.999:  28.714 ms/op
                 listUser·p0.9999: 29.065 ms/op
                 listUser·p1.00:   29.065 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 1893
  mean =     16.769 ±(99.9%) 0.312 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 5 
    [ 5.000,  7.500) = 18 
    [ 7.500, 10.000) = 71 
    [10.000, 12.500) = 146 
    [12.500, 15.000) = 353 
    [15.000, 17.500) = 657 
    [17.500, 20.000) = 122 
    [20.000, 22.500) = 323 
    [22.500, 25.000) = 154 
    [25.000, 27.500) = 38 

  Percentiles, ms/op:
      p(0.0000) =      2.998 ms/op
     p(50.0000) =     15.598 ms/op
     p(90.0000) =     22.577 ms/op
     p(95.0000) =     23.331 ms/op
     p(99.0000) =     26.378 ms/op
     p(99.9000) =     28.714 ms/op
     p(99.9900) =     29.065 ms/op
     p(99.9990) =     29.065 ms/op
     p(99.9999) =     29.065 ms/op
    p(100.0000) =     29.065 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode   Cnt   Score   Error   Units
Client.createUser                      thrpt         2.379          ops/ms
Client.existUser                       thrpt         7.154          ops/ms
Client.getUser                         thrpt         4.603          ops/ms
Client.listUser                        thrpt         1.249          ops/ms
Client.createUser                       avgt         8.537           ms/op
Client.existUser                        avgt         4.744           ms/op
Client.getUser                          avgt         5.377           ms/op
Client.listUser                         avgt        19.290           ms/op
Client.createUser                     sample  3754   8.507 ± 0.183   ms/op
Client.createUser:createUser·p0.00    sample         1.651           ms/op
Client.createUser:createUser·p0.50    sample         7.889           ms/op
Client.createUser:createUser·p0.90    sample         9.339           ms/op
Client.createUser:createUser·p0.95    sample        13.603           ms/op
Client.createUser:createUser·p0.99    sample        16.843           ms/op
Client.createUser:createUser·p0.999   sample        40.517           ms/op
Client.createUser:createUser·p0.9999  sample        40.698           ms/op
Client.createUser:createUser·p1.00    sample        40.698           ms/op
Client.existUser                      sample  6759   4.740 ± 0.060   ms/op
Client.existUser:existUser·p0.00      sample         1.327           ms/op
Client.existUser:existUser·p0.50      sample         4.620           ms/op
Client.existUser:existUser·p0.90      sample         5.104           ms/op
Client.existUser:existUser·p0.95      sample         5.382           ms/op
Client.existUser:existUser·p0.99      sample        12.681           ms/op
Client.existUser:existUser·p0.999     sample        13.304           ms/op
Client.existUser:existUser·p0.9999    sample        14.139           ms/op
Client.existUser:existUser·p1.00      sample        14.139           ms/op
Client.getUser                        sample  6634   4.889 ± 0.090   ms/op
Client.getUser:getUser·p0.00          sample         2.236           ms/op
Client.getUser:getUser·p0.50          sample         4.555           ms/op
Client.getUser:getUser·p0.90          sample         5.186           ms/op
Client.getUser:getUser·p0.95          sample         6.218           ms/op
Client.getUser:getUser·p0.99          sample        14.189           ms/op
Client.getUser:getUser·p0.999         sample        31.228           ms/op
Client.getUser:getUser·p0.9999        sample        31.326           ms/op
Client.getUser:getUser·p1.00          sample        31.326           ms/op
Client.listUser                       sample  1893  16.769 ± 0.312   ms/op
Client.listUser:listUser·p0.00        sample         2.998           ms/op
Client.listUser:listUser·p0.50        sample        15.598           ms/op
Client.listUser:listUser·p0.90        sample        22.577           ms/op
Client.listUser:listUser·p0.95        sample        23.331           ms/op
Client.listUser:listUser·p0.99        sample        26.378           ms/op
Client.listUser:listUser·p0.999       sample        28.714           ms/op
Client.listUser:listUser·p0.9999      sample        29.065           ms/op
Client.listUser:listUser·p1.00        sample        29.065           ms/op
