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
# Warmup Iteration   1: 0.539 ops/ms
Iteration   1: 1.099 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  1.099 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:28
# Fork: 1 of 1
# Warmup Iteration   1: 1.182 ops/ms
Iteration   1: 3.889 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  3.889 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:19
# Fork: 1 of 1
# Warmup Iteration   1: 1.018 ops/ms
Iteration   1: 2.024 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  2.024 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:11
# Fork: 1 of 1
# Warmup Iteration   1: 0.509 ops/ms
Iteration   1: 0.775 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  0.775 ops/ms


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

# Run progress: 33.33% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 26.483 ±(99.9%) 0.493 ms/op
Iteration   1: 17.615 ±(99.9%) 0.081 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  17.615 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 19.967 ±(99.9%) 0.352 ms/op
Iteration   1: 10.722 ±(99.9%) 0.035 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  10.722 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:47
# Fork: 1 of 1
# Warmup Iteration   1: 19.073 ±(99.9%) 0.304 ms/op
Iteration   1: 11.743 ±(99.9%) 0.089 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  11.743 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:39
# Fork: 1 of 1
# Warmup Iteration   1: 47.197 ±(99.9%) 0.990 ms/op
Iteration   1: 28.047 ±(99.9%) 0.169 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  28.047 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:31
# Fork: 1 of 1
# Warmup Iteration   1: 25.396 ±(99.9%) 0.926 ms/op
Iteration   1: 12.640 ±(99.9%) 0.389 ms/op
                 createUser·p0.00:   4.645 ms/op
                 createUser·p0.50:   11.125 ms/op
                 createUser·p0.90:   19.972 ms/op
                 createUser·p0.95:   27.181 ms/op
                 createUser·p0.99:   34.193 ms/op
                 createUser·p0.999:  39.322 ms/op
                 createUser·p0.9999: 39.387 ms/op
                 createUser·p1.00:   39.387 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 2524
  mean =     12.640 ±(99.9%) 0.389 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 47 
    [ 5.000,  7.500) = 246 
    [ 7.500, 10.000) = 323 
    [10.000, 12.500) = 1238 
    [12.500, 15.000) = 251 
    [15.000, 17.500) = 59 
    [17.500, 20.000) = 109 
    [20.000, 22.500) = 38 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 66 
    [27.500, 30.000) = 55 
    [30.000, 32.500) = 26 
    [32.500, 35.000) = 16 
    [35.000, 37.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      4.645 ms/op
     p(50.0000) =     11.125 ms/op
     p(90.0000) =     19.972 ms/op
     p(95.0000) =     27.181 ms/op
     p(99.0000) =     34.193 ms/op
     p(99.9000) =     39.322 ms/op
     p(99.9900) =     39.387 ms/op
     p(99.9990) =     39.387 ms/op
     p(99.9999) =     39.387 ms/op
    p(100.0000) =     39.387 ms/op


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

# Run progress: 75.00% complete, ETA 00:00:23
# Fork: 1 of 1
# Warmup Iteration   1: 15.797 ±(99.9%) 0.441 ms/op
Iteration   1: 8.282 ±(99.9%) 0.168 ms/op
                 existUser·p0.00:   2.314 ms/op
                 existUser·p0.50:   7.832 ms/op
                 existUser·p0.90:   9.929 ms/op
                 existUser·p0.95:   12.239 ms/op
                 existUser·p0.99:   24.576 ms/op
                 existUser·p0.999:  29.862 ms/op
                 existUser·p0.9999: 30.081 ms/op
                 existUser·p1.00:   30.081 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 3895
  mean =      8.282 ±(99.9%) 0.168 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3 
    [ 2.500,  5.000) = 131 
    [ 5.000,  7.500) = 1299 
    [ 7.500, 10.000) = 2097 
    [10.000, 12.500) = 190 
    [12.500, 15.000) = 15 
    [15.000, 17.500) = 38 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 47 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 4 
    [27.500, 30.000) = 24 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.314 ms/op
     p(50.0000) =      7.832 ms/op
     p(90.0000) =      9.929 ms/op
     p(95.0000) =     12.239 ms/op
     p(99.0000) =     24.576 ms/op
     p(99.9000) =     29.862 ms/op
     p(99.9900) =     30.081 ms/op
     p(99.9990) =     30.081 ms/op
     p(99.9999) =     30.081 ms/op
    p(100.0000) =     30.081 ms/op


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

# Run progress: 83.33% complete, ETA 00:00:15
# Fork: 1 of 1
# Warmup Iteration   1: 25.416 ±(99.9%) 1.159 ms/op
Iteration   1: 9.790 ±(99.9%) 0.294 ms/op
                 getUser·p0.00:   3.174 ms/op
                 getUser·p0.50:   8.110 ms/op
                 getUser·p0.90:   14.143 ms/op
                 getUser·p0.95:   19.169 ms/op
                 getUser·p0.99:   34.350 ms/op
                 getUser·p0.999:  43.319 ms/op
                 getUser·p0.9999: 43.385 ms/op
                 getUser·p1.00:   43.385 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 3253
  mean =      9.790 ±(99.9%) 0.294 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 37 
    [ 5.000, 10.000) = 2279 
    [10.000, 15.000) = 637 
    [15.000, 20.000) = 181 
    [20.000, 25.000) = 30 
    [25.000, 30.000) = 26 
    [30.000, 35.000) = 34 
    [35.000, 40.000) = 14 
    [40.000, 45.000) = 15 

  Percentiles, ms/op:
      p(0.0000) =      3.174 ms/op
     p(50.0000) =      8.110 ms/op
     p(90.0000) =     14.143 ms/op
     p(95.0000) =     19.169 ms/op
     p(99.0000) =     34.350 ms/op
     p(99.9000) =     43.319 ms/op
     p(99.9900) =     43.385 ms/op
     p(99.9990) =     43.385 ms/op
     p(99.9999) =     43.385 ms/op
    p(100.0000) =     43.385 ms/op


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
# Warmup Iteration   1: 42.494 ±(99.9%) 1.451 ms/op
Iteration   1: 27.202 ±(99.9%) 0.556 ms/op
                 listUser·p0.00:   15.712 ms/op
                 listUser·p0.50:   25.100 ms/op
                 listUser·p0.90:   35.979 ms/op
                 listUser·p0.95:   38.928 ms/op
                 listUser·p0.99:   44.761 ms/op
                 listUser·p0.999:  53.872 ms/op
                 listUser·p0.9999: 54.002 ms/op
                 listUser·p1.00:   54.002 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 1179
  mean =     27.202 ±(99.9%) 0.556 ms/op

  Histogram, ms/op:
    [10.000, 15.000) = 0 
    [15.000, 20.000) = 52 
    [20.000, 25.000) = 510 
    [25.000, 30.000) = 321 
    [30.000, 35.000) = 154 
    [35.000, 40.000) = 110 
    [40.000, 45.000) = 21 
    [45.000, 50.000) = 6 
    [50.000, 55.000) = 5 

  Percentiles, ms/op:
      p(0.0000) =     15.712 ms/op
     p(50.0000) =     25.100 ms/op
     p(90.0000) =     35.979 ms/op
     p(95.0000) =     38.928 ms/op
     p(99.0000) =     44.761 ms/op
     p(99.9000) =     53.872 ms/op
     p(99.9900) =     54.002 ms/op
     p(99.9990) =     54.002 ms/op
     p(99.9999) =     54.002 ms/op
    p(100.0000) =     54.002 ms/op


# Run complete. Total time: 00:01:35

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode   Cnt   Score   Error   Units
Client.createUser                      thrpt         1.099          ops/ms
Client.existUser                       thrpt         3.889          ops/ms
Client.getUser                         thrpt         2.024          ops/ms
Client.listUser                        thrpt         0.775          ops/ms
Client.createUser                       avgt        17.615           ms/op
Client.existUser                        avgt        10.722           ms/op
Client.getUser                          avgt        11.743           ms/op
Client.listUser                         avgt        28.047           ms/op
Client.createUser                     sample  2524  12.640 ± 0.389   ms/op
Client.createUser:createUser·p0.00    sample         4.645           ms/op
Client.createUser:createUser·p0.50    sample        11.125           ms/op
Client.createUser:createUser·p0.90    sample        19.972           ms/op
Client.createUser:createUser·p0.95    sample        27.181           ms/op
Client.createUser:createUser·p0.99    sample        34.193           ms/op
Client.createUser:createUser·p0.999   sample        39.322           ms/op
Client.createUser:createUser·p0.9999  sample        39.387           ms/op
Client.createUser:createUser·p1.00    sample        39.387           ms/op
Client.existUser                      sample  3895   8.282 ± 0.168   ms/op
Client.existUser:existUser·p0.00      sample         2.314           ms/op
Client.existUser:existUser·p0.50      sample         7.832           ms/op
Client.existUser:existUser·p0.90      sample         9.929           ms/op
Client.existUser:existUser·p0.95      sample        12.239           ms/op
Client.existUser:existUser·p0.99      sample        24.576           ms/op
Client.existUser:existUser·p0.999     sample        29.862           ms/op
Client.existUser:existUser·p0.9999    sample        30.081           ms/op
Client.existUser:existUser·p1.00      sample        30.081           ms/op
Client.getUser                        sample  3253   9.790 ± 0.294   ms/op
Client.getUser:getUser·p0.00          sample         3.174           ms/op
Client.getUser:getUser·p0.50          sample         8.110           ms/op
Client.getUser:getUser·p0.90          sample        14.143           ms/op
Client.getUser:getUser·p0.95          sample        19.169           ms/op
Client.getUser:getUser·p0.99          sample        34.350           ms/op
Client.getUser:getUser·p0.999         sample        43.319           ms/op
Client.getUser:getUser·p0.9999        sample        43.385           ms/op
Client.getUser:getUser·p1.00          sample        43.385           ms/op
Client.listUser                       sample  1179  27.202 ± 0.556   ms/op
Client.listUser:listUser·p0.00        sample        15.712           ms/op
Client.listUser:listUser·p0.50        sample        25.100           ms/op
Client.listUser:listUser·p0.90        sample        35.979           ms/op
Client.listUser:listUser·p0.95        sample        38.928           ms/op
Client.listUser:listUser·p0.99        sample        44.761           ms/op
Client.listUser:listUser·p0.999       sample        53.872           ms/op
Client.listUser:listUser·p0.9999      sample        54.002           ms/op
Client.listUser:listUser·p1.00        sample        54.002           ms/op
