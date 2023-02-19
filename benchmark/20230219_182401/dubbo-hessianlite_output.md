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
# Warmup Iteration   1: 0.362 ops/ms
Iteration   1: 0.877 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  0.877 ops/ms


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
# Warmup Iteration   1: 1.047 ops/ms
Iteration   1: 3.103 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  3.103 ops/ms


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
# Warmup Iteration   1: 1.057 ops/ms
Iteration   1: 2.403 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  2.403 ops/ms


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
# Warmup Iteration   1: 0.543 ops/ms
Iteration   1: 0.811 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  0.811 ops/ms


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
# Warmup Iteration   1: 28.907 ±(99.9%) 0.949 ms/op
Iteration   1: 16.636 ±(99.9%) 0.247 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  16.636 ms/op


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
# Warmup Iteration   1: 20.562 ±(99.9%) 0.288 ms/op
Iteration   1: 9.797 ±(99.9%) 0.175 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  9.797 ms/op


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
# Warmup Iteration   1: 25.046 ±(99.9%) 0.578 ms/op
Iteration   1: 11.363 ±(99.9%) 0.067 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  11.363 ms/op


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
# Warmup Iteration   1: 50.222 ±(99.9%) 1.820 ms/op
Iteration   1: 35.106 ±(99.9%) 0.439 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  35.106 ms/op


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
# Warmup Iteration   1: 23.398 ±(99.9%) 0.852 ms/op
Iteration   1: 14.282 ±(99.9%) 0.525 ms/op
                 createUser·p0.00:   0.988 ms/op
                 createUser·p0.50:   11.747 ms/op
                 createUser·p0.90:   22.829 ms/op
                 createUser·p0.95:   27.792 ms/op
                 createUser·p0.99:   49.421 ms/op
                 createUser·p0.999:  63.359 ms/op
                 createUser·p0.9999: 63.504 ms/op
                 createUser·p1.00:   63.504 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 2218
  mean =     14.282 ±(99.9%) 0.525 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 9 
    [ 5.000, 10.000) = 155 
    [10.000, 15.000) = 1591 
    [15.000, 20.000) = 184 
    [20.000, 25.000) = 90 
    [25.000, 30.000) = 108 
    [30.000, 35.000) = 24 
    [35.000, 40.000) = 6 
    [40.000, 45.000) = 24 
    [45.000, 50.000) = 6 
    [50.000, 55.000) = 4 
    [55.000, 60.000) = 1 
    [60.000, 65.000) = 16 

  Percentiles, ms/op:
      p(0.0000) =      0.988 ms/op
     p(50.0000) =     11.747 ms/op
     p(90.0000) =     22.829 ms/op
     p(95.0000) =     27.792 ms/op
     p(99.0000) =     49.421 ms/op
     p(99.9000) =     63.359 ms/op
     p(99.9900) =     63.504 ms/op
     p(99.9990) =     63.504 ms/op
     p(99.9999) =     63.504 ms/op
    p(100.0000) =     63.504 ms/op


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
# Warmup Iteration   1: 19.165 ±(99.9%) 0.592 ms/op
Iteration   1: 10.223 ±(99.9%) 0.312 ms/op
                 existUser·p0.00:   1.046 ms/op
                 existUser·p0.50:   8.700 ms/op
                 existUser·p0.90:   16.351 ms/op
                 existUser·p0.95:   22.512 ms/op
                 existUser·p0.99:   33.227 ms/op
                 existUser·p0.999:  36.168 ms/op
                 existUser·p0.9999: 36.372 ms/op
                 existUser·p1.00:   36.372 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 3122
  mean =     10.223 ±(99.9%) 0.312 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6 
    [ 2.500,  5.000) = 232 
    [ 5.000,  7.500) = 241 
    [ 7.500, 10.000) = 1817 
    [10.000, 12.500) = 239 
    [12.500, 15.000) = 156 
    [15.000, 17.500) = 182 
    [17.500, 20.000) = 70 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 64 
    [25.000, 27.500) = 16 
    [27.500, 30.000) = 46 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 21 
    [35.000, 37.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      1.046 ms/op
     p(50.0000) =      8.700 ms/op
     p(90.0000) =     16.351 ms/op
     p(95.0000) =     22.512 ms/op
     p(99.0000) =     33.227 ms/op
     p(99.9000) =     36.168 ms/op
     p(99.9900) =     36.372 ms/op
     p(99.9990) =     36.372 ms/op
     p(99.9999) =     36.372 ms/op
    p(100.0000) =     36.372 ms/op


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
# Warmup Iteration   1: 19.464 ±(99.9%) 0.737 ms/op
Iteration   1: 9.120 ±(99.9%) 0.236 ms/op
                 getUser·p0.00:   1.448 ms/op
                 getUser·p0.50:   7.750 ms/op
                 getUser·p0.90:   15.471 ms/op
                 getUser·p0.95:   19.071 ms/op
                 getUser·p0.99:   23.626 ms/op
                 getUser·p0.999:  35.751 ms/op
                 getUser·p0.9999: 36.241 ms/op
                 getUser·p1.00:   36.241 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 3488
  mean =      9.120 ±(99.9%) 0.236 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4 
    [ 2.500,  5.000) = 144 
    [ 5.000,  7.500) = 1367 
    [ 7.500, 10.000) = 1197 
    [10.000, 12.500) = 358 
    [12.500, 15.000) = 38 
    [15.000, 17.500) = 126 
    [17.500, 20.000) = 125 
    [20.000, 22.500) = 76 
    [22.500, 25.000) = 26 
    [25.000, 27.500) = 7 
    [27.500, 30.000) = 5 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 4 
    [35.000, 37.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      1.448 ms/op
     p(50.0000) =      7.750 ms/op
     p(90.0000) =     15.471 ms/op
     p(95.0000) =     19.071 ms/op
     p(99.0000) =     23.626 ms/op
     p(99.9000) =     35.751 ms/op
     p(99.9900) =     36.241 ms/op
     p(99.9990) =     36.241 ms/op
     p(99.9999) =     36.241 ms/op
    p(100.0000) =     36.241 ms/op


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
# Warmup Iteration   1: 50.497 ±(99.9%) 2.383 ms/op
Iteration   1: 28.585 ±(99.9%) 0.910 ms/op
                 listUser·p0.00:   5.243 ms/op
                 listUser·p0.50:   26.804 ms/op
                 listUser·p0.90:   40.174 ms/op
                 listUser·p0.95:   43.732 ms/op
                 listUser·p0.99:   55.964 ms/op
                 listUser·p0.999:  61.752 ms/op
                 listUser·p0.9999: 61.866 ms/op
                 listUser·p1.00:   61.866 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 1133
  mean =     28.585 ±(99.9%) 0.910 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 0 
    [ 5.000, 10.000) = 18 
    [10.000, 15.000) = 13 
    [15.000, 20.000) = 82 
    [20.000, 25.000) = 400 
    [25.000, 30.000) = 155 
    [30.000, 35.000) = 190 
    [35.000, 40.000) = 153 
    [40.000, 45.000) = 74 
    [45.000, 50.000) = 10 
    [50.000, 55.000) = 20 
    [55.000, 60.000) = 15 
    [60.000, 65.000) = 3 

  Percentiles, ms/op:
      p(0.0000) =      5.243 ms/op
     p(50.0000) =     26.804 ms/op
     p(90.0000) =     40.174 ms/op
     p(95.0000) =     43.732 ms/op
     p(99.0000) =     55.964 ms/op
     p(99.9000) =     61.752 ms/op
     p(99.9900) =     61.866 ms/op
     p(99.9990) =     61.866 ms/op
     p(99.9999) =     61.866 ms/op
    p(100.0000) =     61.866 ms/op


# Run complete. Total time: 00:01:35

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode   Cnt   Score   Error   Units
Client.createUser                      thrpt         0.877          ops/ms
Client.existUser                       thrpt         3.103          ops/ms
Client.getUser                         thrpt         2.403          ops/ms
Client.listUser                        thrpt         0.811          ops/ms
Client.createUser                       avgt        16.636           ms/op
Client.existUser                        avgt         9.797           ms/op
Client.getUser                          avgt        11.363           ms/op
Client.listUser                         avgt        35.106           ms/op
Client.createUser                     sample  2218  14.282 ± 0.525   ms/op
Client.createUser:createUser·p0.00    sample         0.988           ms/op
Client.createUser:createUser·p0.50    sample        11.747           ms/op
Client.createUser:createUser·p0.90    sample        22.829           ms/op
Client.createUser:createUser·p0.95    sample        27.792           ms/op
Client.createUser:createUser·p0.99    sample        49.421           ms/op
Client.createUser:createUser·p0.999   sample        63.359           ms/op
Client.createUser:createUser·p0.9999  sample        63.504           ms/op
Client.createUser:createUser·p1.00    sample        63.504           ms/op
Client.existUser                      sample  3122  10.223 ± 0.312   ms/op
Client.existUser:existUser·p0.00      sample         1.046           ms/op
Client.existUser:existUser·p0.50      sample         8.700           ms/op
Client.existUser:existUser·p0.90      sample        16.351           ms/op
Client.existUser:existUser·p0.95      sample        22.512           ms/op
Client.existUser:existUser·p0.99      sample        33.227           ms/op
Client.existUser:existUser·p0.999     sample        36.168           ms/op
Client.existUser:existUser·p0.9999    sample        36.372           ms/op
Client.existUser:existUser·p1.00      sample        36.372           ms/op
Client.getUser                        sample  3488   9.120 ± 0.236   ms/op
Client.getUser:getUser·p0.00          sample         1.448           ms/op
Client.getUser:getUser·p0.50          sample         7.750           ms/op
Client.getUser:getUser·p0.90          sample        15.471           ms/op
Client.getUser:getUser·p0.95          sample        19.071           ms/op
Client.getUser:getUser·p0.99          sample        23.626           ms/op
Client.getUser:getUser·p0.999         sample        35.751           ms/op
Client.getUser:getUser·p0.9999        sample        36.241           ms/op
Client.getUser:getUser·p1.00          sample        36.241           ms/op
Client.listUser                       sample  1133  28.585 ± 0.910   ms/op
Client.listUser:listUser·p0.00        sample         5.243           ms/op
Client.listUser:listUser·p0.50        sample        26.804           ms/op
Client.listUser:listUser·p0.90        sample        40.174           ms/op
Client.listUser:listUser·p0.95        sample        43.732           ms/op
Client.listUser:listUser·p0.99        sample        55.964           ms/op
Client.listUser:listUser·p0.999       sample        61.752           ms/op
Client.listUser:listUser·p0.9999      sample        61.866           ms/op
Client.listUser:listUser·p1.00        sample        61.866           ms/op
