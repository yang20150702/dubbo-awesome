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
# Warmup Iteration   1: 0.571 ops/ms
Iteration   1: 1.515 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  1.515 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:23
# Fork: 1 of 1
# Warmup Iteration   1: 1.829 ops/ms
Iteration   1: 4.543 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  4.543 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:14
# Fork: 1 of 1
# Warmup Iteration   1: 1.596 ops/ms
Iteration   1: 3.186 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.186 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:07
# Fork: 1 of 1
# Warmup Iteration   1: 0.704 ops/ms
Iteration   1: 1.061 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  1.061 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:59
# Fork: 1 of 1
# Warmup Iteration   1: 25.425 ±(99.9%) 0.362 ms/op
Iteration   1: 13.324 ±(99.9%) 0.050 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  13.324 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:52
# Fork: 1 of 1
# Warmup Iteration   1: 16.178 ±(99.9%) 0.221 ms/op
Iteration   1: 6.266 ±(99.9%) 0.030 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  6.266 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:44
# Fork: 1 of 1
# Warmup Iteration   1: 16.422 ±(99.9%) 0.543 ms/op
Iteration   1: 7.021 ±(99.9%) 0.099 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  7.021 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:37
# Fork: 1 of 1
# Warmup Iteration   1: 35.859 ±(99.9%) 0.957 ms/op
Iteration   1: 22.838 ±(99.9%) 0.256 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  22.838 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:29
# Fork: 1 of 1
# Warmup Iteration   1: 18.407 ±(99.9%) 0.492 ms/op
Iteration   1: 8.010 ±(99.9%) 0.159 ms/op
                 createUser·p0.00:   2.785 ms/op
                 createUser·p0.50:   7.963 ms/op
                 createUser·p0.90:   9.552 ms/op
                 createUser·p0.95:   12.976 ms/op
                 createUser·p0.99:   19.114 ms/op
                 createUser·p0.999:  31.521 ms/op
                 createUser·p0.9999: 31.556 ms/op
                 createUser·p1.00:   31.556 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 4056
  mean =      8.010 ±(99.9%) 0.159 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 648 
    [ 5.000,  7.500) = 213 
    [ 7.500, 10.000) = 2812 
    [10.000, 12.500) = 158 
    [12.500, 15.000) = 90 
    [15.000, 17.500) = 90 
    [17.500, 20.000) = 9 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 2 
    [27.500, 30.000) = 6 
    [30.000, 32.500) = 24 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.785 ms/op
     p(50.0000) =      7.963 ms/op
     p(90.0000) =      9.552 ms/op
     p(95.0000) =     12.976 ms/op
     p(99.0000) =     19.114 ms/op
     p(99.9000) =     31.521 ms/op
     p(99.9900) =     31.556 ms/op
     p(99.9990) =     31.556 ms/op
     p(99.9999) =     31.556 ms/op
    p(100.0000) =     31.556 ms/op


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

# Run progress: 75.00% complete, ETA 00:00:22
# Fork: 1 of 1
# Warmup Iteration   1: 9.901 ±(99.9%) 0.295 ms/op
Iteration   1: 4.886 ±(99.9%) 0.099 ms/op
                 existUser·p0.00:   1.009 ms/op
                 existUser·p0.50:   4.211 ms/op
                 existUser·p0.90:   6.210 ms/op
                 existUser·p0.95:   6.644 ms/op
                 existUser·p0.99:   16.712 ms/op
                 existUser·p0.999:  24.953 ms/op
                 existUser·p0.9999: 33.882 ms/op
                 existUser·p1.00:   33.882 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 6616
  mean =      4.886 ±(99.9%) 0.099 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 111 
    [ 2.500,  5.000) = 4095 
    [ 5.000,  7.500) = 2142 
    [ 7.500, 10.000) = 63 
    [10.000, 12.500) = 61 
    [12.500, 15.000) = 64 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 9 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 2 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 4 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.009 ms/op
     p(50.0000) =      4.211 ms/op
     p(90.0000) =      6.210 ms/op
     p(95.0000) =      6.644 ms/op
     p(99.0000) =     16.712 ms/op
     p(99.9000) =     24.953 ms/op
     p(99.9900) =     33.882 ms/op
     p(99.9990) =     33.882 ms/op
     p(99.9999) =     33.882 ms/op
    p(100.0000) =     33.882 ms/op


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
# Warmup Iteration   1: 13.236 ±(99.9%) 0.468 ms/op
Iteration   1: 5.863 ±(99.9%) 0.129 ms/op
                 getUser·p0.00:   2.050 ms/op
                 getUser·p0.50:   5.448 ms/op
                 getUser·p0.90:   7.152 ms/op
                 getUser·p0.95:   8.929 ms/op
                 getUser·p0.99:   16.269 ms/op
                 getUser·p0.999:  35.196 ms/op
                 getUser·p0.9999: 35.848 ms/op
                 getUser·p1.00:   35.848 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 5475
  mean =      5.863 ±(99.9%) 0.129 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2 
    [ 2.500,  5.000) = 1888 
    [ 5.000,  7.500) = 3128 
    [ 7.500, 10.000) = 257 
    [10.000, 12.500) = 54 
    [12.500, 15.000) = 53 
    [15.000, 17.500) = 47 
    [17.500, 20.000) = 8 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 6 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 26 
    [35.000, 37.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      2.050 ms/op
     p(50.0000) =      5.448 ms/op
     p(90.0000) =      7.152 ms/op
     p(95.0000) =      8.929 ms/op
     p(99.0000) =     16.269 ms/op
     p(99.9000) =     35.196 ms/op
     p(99.9900) =     35.848 ms/op
     p(99.9990) =     35.848 ms/op
     p(99.9999) =     35.848 ms/op
    p(100.0000) =     35.848 ms/op


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
# Warmup Iteration   1: 33.515 ±(99.9%) 1.072 ms/op
Iteration   1: 20.077 ±(99.9%) 0.405 ms/op
                 listUser·p0.00:   13.189 ms/op
                 listUser·p0.50:   19.268 ms/op
                 listUser·p0.90:   27.086 ms/op
                 listUser·p0.95:   30.995 ms/op
                 listUser·p0.99:   38.462 ms/op
                 listUser·p0.999:  43.396 ms/op
                 listUser·p0.9999: 43.909 ms/op
                 listUser·p1.00:   43.909 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 1601
  mean =     20.077 ±(99.9%) 0.405 ms/op

  Histogram, ms/op:
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 7 
    [15.000, 17.500) = 496 
    [17.500, 20.000) = 654 
    [20.000, 22.500) = 207 
    [22.500, 25.000) = 47 
    [25.000, 27.500) = 31 
    [27.500, 30.000) = 36 
    [30.000, 32.500) = 63 
    [32.500, 35.000) = 10 
    [35.000, 37.500) = 29 
    [37.500, 40.000) = 9 
    [40.000, 42.500) = 9 
    [42.500, 45.000) = 3 
    [45.000, 47.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =     13.189 ms/op
     p(50.0000) =     19.268 ms/op
     p(90.0000) =     27.086 ms/op
     p(95.0000) =     30.995 ms/op
     p(99.0000) =     38.462 ms/op
     p(99.9000) =     43.396 ms/op
     p(99.9900) =     43.909 ms/op
     p(99.9990) =     43.909 ms/op
     p(99.9999) =     43.909 ms/op
    p(100.0000) =     43.909 ms/op


# Run complete. Total time: 00:01:29

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode   Cnt   Score   Error   Units
Client.createUser                      thrpt         1.515          ops/ms
Client.existUser                       thrpt         4.543          ops/ms
Client.getUser                         thrpt         3.186          ops/ms
Client.listUser                        thrpt         1.061          ops/ms
Client.createUser                       avgt        13.324           ms/op
Client.existUser                        avgt         6.266           ms/op
Client.getUser                          avgt         7.021           ms/op
Client.listUser                         avgt        22.838           ms/op
Client.createUser                     sample  4056   8.010 ± 0.159   ms/op
Client.createUser:createUser·p0.00    sample         2.785           ms/op
Client.createUser:createUser·p0.50    sample         7.963           ms/op
Client.createUser:createUser·p0.90    sample         9.552           ms/op
Client.createUser:createUser·p0.95    sample        12.976           ms/op
Client.createUser:createUser·p0.99    sample        19.114           ms/op
Client.createUser:createUser·p0.999   sample        31.521           ms/op
Client.createUser:createUser·p0.9999  sample        31.556           ms/op
Client.createUser:createUser·p1.00    sample        31.556           ms/op
Client.existUser                      sample  6616   4.886 ± 0.099   ms/op
Client.existUser:existUser·p0.00      sample         1.009           ms/op
Client.existUser:existUser·p0.50      sample         4.211           ms/op
Client.existUser:existUser·p0.90      sample         6.210           ms/op
Client.existUser:existUser·p0.95      sample         6.644           ms/op
Client.existUser:existUser·p0.99      sample        16.712           ms/op
Client.existUser:existUser·p0.999     sample        24.953           ms/op
Client.existUser:existUser·p0.9999    sample        33.882           ms/op
Client.existUser:existUser·p1.00      sample        33.882           ms/op
Client.getUser                        sample  5475   5.863 ± 0.129   ms/op
Client.getUser:getUser·p0.00          sample         2.050           ms/op
Client.getUser:getUser·p0.50          sample         5.448           ms/op
Client.getUser:getUser·p0.90          sample         7.152           ms/op
Client.getUser:getUser·p0.95          sample         8.929           ms/op
Client.getUser:getUser·p0.99          sample        16.269           ms/op
Client.getUser:getUser·p0.999         sample        35.196           ms/op
Client.getUser:getUser·p0.9999        sample        35.848           ms/op
Client.getUser:getUser·p1.00          sample        35.848           ms/op
Client.listUser                       sample  1601  20.077 ± 0.405   ms/op
Client.listUser:listUser·p0.00        sample        13.189           ms/op
Client.listUser:listUser·p0.50        sample        19.268           ms/op
Client.listUser:listUser·p0.90        sample        27.086           ms/op
Client.listUser:listUser·p0.95        sample        30.995           ms/op
Client.listUser:listUser·p0.99        sample        38.462           ms/op
Client.listUser:listUser·p0.999       sample        43.396           ms/op
Client.listUser:listUser·p0.9999      sample        43.909           ms/op
Client.listUser:listUser·p1.00        sample        43.909           ms/op
