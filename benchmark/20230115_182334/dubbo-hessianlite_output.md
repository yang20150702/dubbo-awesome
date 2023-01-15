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
# Warmup Iteration   1: 0.715 ops/ms
Iteration   1: 1.553 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  1.553 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:28
# Fork: 1 of 1
# Warmup Iteration   1: 1.351 ops/ms
Iteration   1: 3.405 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  3.405 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 1.115 ops/ms
Iteration   1: 2.624 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  2.624 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 0.588 ops/ms
Iteration   1: 0.882 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  0.882 ops/ms


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

# Run progress: 33.33% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 30.400 ±(99.9%) 0.710 ms/op
Iteration   1: 17.376 ±(99.9%) 0.137 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  17.376 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 17.428 ±(99.9%) 0.256 ms/op
Iteration   1: 7.825 ±(99.9%) 0.158 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  7.825 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:47
# Fork: 1 of 1
# Warmup Iteration   1: 26.565 ±(99.9%) 0.653 ms/op
Iteration   1: 9.305 ±(99.9%) 0.038 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  9.305 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:39
# Fork: 1 of 1
# Warmup Iteration   1: 39.772 ±(99.9%) 0.879 ms/op
Iteration   1: 27.003 ±(99.9%) 0.340 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  27.003 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:31
# Fork: 1 of 1
# Warmup Iteration   1: 24.343 ±(99.9%) 1.150 ms/op
Iteration   1: 11.943 ±(99.9%) 0.311 ms/op
                 createUser·p0.00:   3.715 ms/op
                 createUser·p0.50:   10.666 ms/op
                 createUser·p0.90:   16.246 ms/op
                 createUser·p0.95:   18.439 ms/op
                 createUser·p0.99:   42.099 ms/op
                 createUser·p0.999:  50.157 ms/op
                 createUser·p0.9999: 50.266 ms/op
                 createUser·p1.00:   50.266 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 2661
  mean =     11.943 ±(99.9%) 0.311 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 11 
    [ 5.000, 10.000) = 908 
    [10.000, 15.000) = 1349 
    [15.000, 20.000) = 317 
    [20.000, 25.000) = 10 
    [25.000, 30.000) = 34 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 24 
    [45.000, 50.000) = 4 
    [50.000, 55.000) = 4 

  Percentiles, ms/op:
      p(0.0000) =      3.715 ms/op
     p(50.0000) =     10.666 ms/op
     p(90.0000) =     16.246 ms/op
     p(95.0000) =     18.439 ms/op
     p(99.0000) =     42.099 ms/op
     p(99.9000) =     50.157 ms/op
     p(99.9900) =     50.266 ms/op
     p(99.9990) =     50.266 ms/op
     p(99.9999) =     50.266 ms/op
    p(100.0000) =     50.266 ms/op


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

# Run progress: 75.00% complete, ETA 00:00:23
# Fork: 1 of 1
# Warmup Iteration   1: 15.430 ±(99.9%) 0.433 ms/op
Iteration   1: 6.756 ±(99.9%) 0.146 ms/op
                 existUser·p0.00:   1.346 ms/op
                 existUser·p0.50:   7.102 ms/op
                 existUser·p0.90:   9.372 ms/op
                 existUser·p0.95:   9.978 ms/op
                 existUser·p0.99:   18.281 ms/op
                 existUser·p0.999:  26.338 ms/op
                 existUser·p0.9999: 29.098 ms/op
                 existUser·p1.00:   29.098 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 4741
  mean =      6.756 ±(99.9%) 0.146 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14 
    [ 2.500,  5.000) = 1565 
    [ 5.000,  7.500) = 1210 
    [ 7.500, 10.000) = 1733 
    [10.000, 12.500) = 97 
    [12.500, 15.000) = 3 
    [15.000, 17.500) = 49 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 17 

  Percentiles, ms/op:
      p(0.0000) =      1.346 ms/op
     p(50.0000) =      7.102 ms/op
     p(90.0000) =      9.372 ms/op
     p(95.0000) =      9.978 ms/op
     p(99.0000) =     18.281 ms/op
     p(99.9000) =     26.338 ms/op
     p(99.9900) =     29.098 ms/op
     p(99.9990) =     29.098 ms/op
     p(99.9999) =     29.098 ms/op
    p(100.0000) =     29.098 ms/op


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

# Run progress: 83.33% complete, ETA 00:00:15
# Fork: 1 of 1
# Warmup Iteration   1: 21.796 ±(99.9%) 0.851 ms/op
Iteration   1: 11.577 ±(99.9%) 0.455 ms/op
                 getUser·p0.00:   3.908 ms/op
                 getUser·p0.50:   9.175 ms/op
                 getUser·p0.90:   21.365 ms/op
                 getUser·p0.95:   30.876 ms/op
                 getUser·p0.99:   37.618 ms/op
                 getUser·p0.999:  43.774 ms/op
                 getUser·p0.9999: 44.171 ms/op
                 getUser·p1.00:   44.171 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 2764
  mean =     11.577 ±(99.9%) 0.455 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 35 
    [ 5.000, 10.000) = 1604 
    [10.000, 15.000) = 754 
    [15.000, 20.000) = 78 
    [20.000, 25.000) = 98 
    [25.000, 30.000) = 37 
    [30.000, 35.000) = 81 
    [35.000, 40.000) = 57 
    [40.000, 45.000) = 20 

  Percentiles, ms/op:
      p(0.0000) =      3.908 ms/op
     p(50.0000) =      9.175 ms/op
     p(90.0000) =     21.365 ms/op
     p(95.0000) =     30.876 ms/op
     p(99.0000) =     37.618 ms/op
     p(99.9000) =     43.774 ms/op
     p(99.9900) =     44.171 ms/op
     p(99.9990) =     44.171 ms/op
     p(99.9999) =     44.171 ms/op
    p(100.0000) =     44.171 ms/op


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
# Warmup Iteration   1: 40.904 ±(99.9%) 1.492 ms/op
Iteration   1: 26.983 ±(99.9%) 0.681 ms/op
                 listUser·p0.00:   8.749 ms/op
                 listUser·p0.50:   24.904 ms/op
                 listUser·p0.90:   38.273 ms/op
                 listUser·p0.95:   41.812 ms/op
                 listUser·p0.99:   48.959 ms/op
                 listUser·p0.999:  56.035 ms/op
                 listUser·p0.9999: 56.099 ms/op
                 listUser·p1.00:   56.099 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 1194
  mean =     26.983 ±(99.9%) 0.681 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 0 
    [ 5.000, 10.000) = 4 
    [10.000, 15.000) = 17 
    [15.000, 20.000) = 58 
    [20.000, 25.000) = 523 
    [25.000, 30.000) = 281 
    [30.000, 35.000) = 154 
    [35.000, 40.000) = 65 
    [40.000, 45.000) = 68 
    [45.000, 50.000) = 15 
    [50.000, 55.000) = 6 

  Percentiles, ms/op:
      p(0.0000) =      8.749 ms/op
     p(50.0000) =     24.904 ms/op
     p(90.0000) =     38.273 ms/op
     p(95.0000) =     41.812 ms/op
     p(99.0000) =     48.959 ms/op
     p(99.9000) =     56.035 ms/op
     p(99.9900) =     56.099 ms/op
     p(99.9990) =     56.099 ms/op
     p(99.9999) =     56.099 ms/op
    p(100.0000) =     56.099 ms/op


# Run complete. Total time: 00:01:34

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode   Cnt   Score   Error   Units
Client.createUser                      thrpt         1.553          ops/ms
Client.existUser                       thrpt         3.405          ops/ms
Client.getUser                         thrpt         2.624          ops/ms
Client.listUser                        thrpt         0.882          ops/ms
Client.createUser                       avgt        17.376           ms/op
Client.existUser                        avgt         7.825           ms/op
Client.getUser                          avgt         9.305           ms/op
Client.listUser                         avgt        27.003           ms/op
Client.createUser                     sample  2661  11.943 ± 0.311   ms/op
Client.createUser:createUser·p0.00    sample         3.715           ms/op
Client.createUser:createUser·p0.50    sample        10.666           ms/op
Client.createUser:createUser·p0.90    sample        16.246           ms/op
Client.createUser:createUser·p0.95    sample        18.439           ms/op
Client.createUser:createUser·p0.99    sample        42.099           ms/op
Client.createUser:createUser·p0.999   sample        50.157           ms/op
Client.createUser:createUser·p0.9999  sample        50.266           ms/op
Client.createUser:createUser·p1.00    sample        50.266           ms/op
Client.existUser                      sample  4741   6.756 ± 0.146   ms/op
Client.existUser:existUser·p0.00      sample         1.346           ms/op
Client.existUser:existUser·p0.50      sample         7.102           ms/op
Client.existUser:existUser·p0.90      sample         9.372           ms/op
Client.existUser:existUser·p0.95      sample         9.978           ms/op
Client.existUser:existUser·p0.99      sample        18.281           ms/op
Client.existUser:existUser·p0.999     sample        26.338           ms/op
Client.existUser:existUser·p0.9999    sample        29.098           ms/op
Client.existUser:existUser·p1.00      sample        29.098           ms/op
Client.getUser                        sample  2764  11.577 ± 0.455   ms/op
Client.getUser:getUser·p0.00          sample         3.908           ms/op
Client.getUser:getUser·p0.50          sample         9.175           ms/op
Client.getUser:getUser·p0.90          sample        21.365           ms/op
Client.getUser:getUser·p0.95          sample        30.876           ms/op
Client.getUser:getUser·p0.99          sample        37.618           ms/op
Client.getUser:getUser·p0.999         sample        43.774           ms/op
Client.getUser:getUser·p0.9999        sample        44.171           ms/op
Client.getUser:getUser·p1.00          sample        44.171           ms/op
Client.listUser                       sample  1194  26.983 ± 0.681   ms/op
Client.listUser:listUser·p0.00        sample         8.749           ms/op
Client.listUser:listUser·p0.50        sample        24.904           ms/op
Client.listUser:listUser·p0.90        sample        38.273           ms/op
Client.listUser:listUser·p0.95        sample        41.812           ms/op
Client.listUser:listUser·p0.99        sample        48.959           ms/op
Client.listUser:listUser·p0.999       sample        56.035           ms/op
Client.listUser:listUser·p0.9999      sample        56.099           ms/op
Client.listUser:listUser·p1.00        sample        56.099           ms/op
