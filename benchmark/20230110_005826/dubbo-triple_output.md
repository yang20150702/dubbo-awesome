# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.678 ops/ms
# Warmup Iteration   2: 3.358 ops/ms
# Warmup Iteration   3: 6.944 ops/ms
Iteration   1: 7.520 ops/ms
Iteration   2: 8.236 ops/ms
Iteration   3: 8.181 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.979 ±(99.9%) 7.271 ops/ms [Average]
  (min, avg, max) = (7.520, 7.979, 8.236), stdev = 0.399
  CI (99.9%): [0.708, 15.250] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:01
# Fork: 1 of 1
# Warmup Iteration   1: 2.339 ops/ms
# Warmup Iteration   2: 7.390 ops/ms
# Warmup Iteration   3: 7.758 ops/ms
Iteration   1: 7.890 ops/ms
Iteration   2: 8.167 ops/ms
Iteration   3: 8.301 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.119 ±(99.9%) 3.831 ops/ms [Average]
  (min, avg, max) = (7.890, 8.119, 8.301), stdev = 0.210
  CI (99.9%): [4.289, 11.950] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:59
# Fork: 1 of 1
# Warmup Iteration   1: 2.205 ops/ms
# Warmup Iteration   2: 6.051 ops/ms
# Warmup Iteration   3: 8.173 ops/ms
Iteration   1: 7.436 ops/ms
Iteration   2: 8.081 ops/ms
Iteration   3: 7.792 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.770 ±(99.9%) 5.894 ops/ms [Average]
  (min, avg, max) = (7.436, 7.770, 8.081), stdev = 0.323
  CI (99.9%): [1.876, 13.663] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.091 ops/ms
# Warmup Iteration   2: 5.699 ops/ms
# Warmup Iteration   3: 6.894 ops/ms
Iteration   1: 6.964 ops/ms
Iteration   2: 7.077 ops/ms
Iteration   3: 6.875 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.972 ±(99.9%) 1.852 ops/ms [Average]
  (min, avg, max) = (6.875, 6.972, 7.077), stdev = 0.102
  CI (99.9%): [5.120, 8.824] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 10.718 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 5.083 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.263 ±(99.9%) 0.004 ms/op
Iteration   1: 3.988 ±(99.9%) 0.011 ms/op
Iteration   2: 4.066 ±(99.9%) 0.005 ms/op
Iteration   3: 3.857 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.970 ±(99.9%) 1.925 ms/op [Average]
  (min, avg, max) = (3.857, 3.970, 4.066), stdev = 0.105
  CI (99.9%): [2.046, 5.895] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 11.298 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 4.400 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.926 ±(99.9%) 0.011 ms/op
Iteration   1: 3.814 ±(99.9%) 0.008 ms/op
Iteration   2: 3.856 ±(99.9%) 0.009 ms/op
Iteration   3: 3.763 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.811 ±(99.9%) 0.846 ms/op [Average]
  (min, avg, max) = (3.763, 3.811, 3.856), stdev = 0.046
  CI (99.9%): [2.964, 4.657] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 11.240 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 4.462 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.246 ±(99.9%) 0.012 ms/op
Iteration   1: 4.102 ±(99.9%) 0.006 ms/op
Iteration   2: 3.908 ±(99.9%) 0.006 ms/op
Iteration   3: 3.880 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.964 ±(99.9%) 2.204 ms/op [Average]
  (min, avg, max) = (3.880, 3.964, 4.102), stdev = 0.121
  CI (99.9%): [1.759, 6.168] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 13.834 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 5.468 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.734 ±(99.9%) 0.010 ms/op
Iteration   1: 4.562 ±(99.9%) 0.016 ms/op
Iteration   2: 4.606 ±(99.9%) 0.007 ms/op
Iteration   3: 4.662 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.610 ±(99.9%) 0.912 ms/op [Average]
  (min, avg, max) = (4.562, 4.610, 4.662), stdev = 0.050
  CI (99.9%): [3.698, 5.522] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 12.943 ±(99.9%) 0.164 ms/op
# Warmup Iteration   2: 4.722 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 4.281 ±(99.9%) 0.018 ms/op
Iteration   1: 4.218 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.671 ms/op
                 createUser·p0.50:   3.957 ms/op
                 createUser·p0.90:   5.112 ms/op
                 createUser·p0.95:   6.562 ms/op
                 createUser·p0.99:   8.667 ms/op
                 createUser·p0.999:  14.766 ms/op
                 createUser·p0.9999: 24.786 ms/op
                 createUser·p1.00:   25.625 ms/op

Iteration   2: 3.945 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.683 ms/op
                 createUser·p0.50:   3.879 ms/op
                 createUser·p0.90:   4.284 ms/op
                 createUser·p0.95:   4.792 ms/op
                 createUser·p0.99:   7.458 ms/op
                 createUser·p0.999:  25.619 ms/op
                 createUser·p0.9999: 28.662 ms/op
                 createUser·p1.00:   29.327 ms/op

Iteration   3: 3.896 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.423 ms/op
                 createUser·p0.50:   3.764 ms/op
                 createUser·p0.90:   4.334 ms/op
                 createUser·p0.95:   4.678 ms/op
                 createUser·p0.99:   6.808 ms/op
                 createUser·p0.999:  26.079 ms/op
                 createUser·p0.9999: 32.761 ms/op
                 createUser·p1.00:   33.948 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 239059
  mean =      4.015 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 272 
    [ 2.500,  5.000) = 224799 
    [ 5.000,  7.500) = 10778 
    [ 7.500, 10.000) = 2416 
    [10.000, 12.500) = 405 
    [12.500, 15.000) = 101 
    [15.000, 17.500) = 13 
    [17.500, 20.000) = 10 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 64 
    [25.000, 27.500) = 93 
    [27.500, 30.000) = 57 
    [30.000, 32.500) = 32 
    [32.500, 35.000) = 10 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.423 ms/op
     p(50.0000) =      3.871 ms/op
     p(90.0000) =      4.538 ms/op
     p(95.0000) =      5.210 ms/op
     p(99.0000) =      8.258 ms/op
     p(99.9000) =     23.626 ms/op
     p(99.9900) =     31.457 ms/op
     p(99.9990) =     33.677 ms/op
     p(99.9999) =     33.948 ms/op
    p(100.0000) =     33.948 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 12.776 ±(99.9%) 0.171 ms/op
# Warmup Iteration   2: 4.515 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 3.996 ±(99.9%) 0.012 ms/op
Iteration   1: 3.746 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.677 ms/op
                 existUser·p0.50:   3.731 ms/op
                 existUser·p0.90:   3.912 ms/op
                 existUser·p0.95:   4.530 ms/op
                 existUser·p0.99:   6.733 ms/op
                 existUser·p0.999:  9.986 ms/op
                 existUser·p0.9999: 24.981 ms/op
                 existUser·p1.00:   25.788 ms/op

Iteration   2: 3.748 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.733 ms/op
                 existUser·p0.50:   3.637 ms/op
                 existUser·p0.90:   4.129 ms/op
                 existUser·p0.95:   4.432 ms/op
                 existUser·p0.99:   6.641 ms/op
                 existUser·p0.999:  16.351 ms/op
                 existUser·p0.9999: 27.656 ms/op
                 existUser·p1.00:   28.901 ms/op

Iteration   3: 3.907 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   1.481 ms/op
                 existUser·p0.50:   3.752 ms/op
                 existUser·p0.90:   4.465 ms/op
                 existUser·p0.95:   4.881 ms/op
                 existUser·p0.99:   7.168 ms/op
                 existUser·p0.999:  26.282 ms/op
                 existUser·p0.9999: 42.759 ms/op
                 existUser·p1.00:   43.581 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 252781
  mean =      3.799 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 244256 
    [ 5.000, 10.000) = 8143 
    [10.000, 15.000) = 126 
    [15.000, 20.000) = 32 
    [20.000, 25.000) = 69 
    [25.000, 30.000) = 103 
    [30.000, 35.000) = 20 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 32 

  Percentiles, ms/op:
      p(0.0000) =      1.481 ms/op
     p(50.0000) =      3.715 ms/op
     p(90.0000) =      4.219 ms/op
     p(95.0000) =      4.661 ms/op
     p(99.0000) =      6.832 ms/op
     p(99.9000) =     16.318 ms/op
     p(99.9900) =     40.763 ms/op
     p(99.9990) =     43.123 ms/op
     p(99.9999) =     43.581 ms/op
    p(100.0000) =     43.581 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 14.269 ±(99.9%) 0.206 ms/op
# Warmup Iteration   2: 4.702 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 4.172 ±(99.9%) 0.014 ms/op
Iteration   1: 3.966 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.358 ms/op
                 getUser·p0.50:   3.801 ms/op
                 getUser·p0.90:   4.489 ms/op
                 getUser·p0.95:   5.063 ms/op
                 getUser·p0.99:   7.881 ms/op
                 getUser·p0.999:  21.168 ms/op
                 getUser·p0.9999: 24.113 ms/op
                 getUser·p1.00:   24.674 ms/op

Iteration   2: 3.857 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.229 ms/op
                 getUser·p0.50:   3.727 ms/op
                 getUser·p0.90:   4.178 ms/op
                 getUser·p0.95:   4.424 ms/op
                 getUser·p0.99:   6.820 ms/op
                 getUser·p0.999:  17.400 ms/op
                 getUser·p0.9999: 28.867 ms/op
                 getUser·p1.00:   29.753 ms/op

Iteration   3: 3.880 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   2.109 ms/op
                 getUser·p0.50:   3.715 ms/op
                 getUser·p0.90:   4.268 ms/op
                 getUser·p0.95:   4.645 ms/op
                 getUser·p0.99:   7.750 ms/op
                 getUser·p0.999:  24.627 ms/op
                 getUser·p0.9999: 30.746 ms/op
                 getUser·p1.00:   32.342 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 245965
  mean =      3.901 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 97 
    [ 2.500,  5.000) = 236517 
    [ 5.000,  7.500) = 6896 
    [ 7.500, 10.000) = 1678 
    [10.000, 12.500) = 369 
    [12.500, 15.000) = 110 
    [15.000, 17.500) = 24 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 73 
    [22.500, 25.000) = 74 
    [25.000, 27.500) = 60 
    [27.500, 30.000) = 47 
    [30.000, 32.500) = 15 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.229 ms/op
     p(50.0000) =      3.744 ms/op
     p(90.0000) =      4.309 ms/op
     p(95.0000) =      4.710 ms/op
     p(99.0000) =      7.487 ms/op
     p(99.9000) =     21.135 ms/op
     p(99.9900) =     29.178 ms/op
     p(99.9990) =     31.200 ms/op
     p(99.9999) =     32.342 ms/op
    p(100.0000) =     32.342 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 13.773 ±(99.9%) 0.199 ms/op
# Warmup Iteration   2: 5.890 ±(99.9%) 0.036 ms/op
# Warmup Iteration   3: 4.911 ±(99.9%) 0.018 ms/op
Iteration   1: 4.824 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   2.154 ms/op
                 listUser·p0.50:   4.555 ms/op
                 listUser·p0.90:   5.464 ms/op
                 listUser·p0.95:   6.963 ms/op
                 listUser·p0.99:   9.130 ms/op
                 listUser·p0.999:  25.803 ms/op
                 listUser·p0.9999: 27.648 ms/op
                 listUser·p1.00:   28.017 ms/op

Iteration   2: 4.612 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.245 ms/op
                 listUser·p0.50:   4.424 ms/op
                 listUser·p0.90:   5.046 ms/op
                 listUser·p0.95:   5.358 ms/op
                 listUser·p0.99:   9.044 ms/op
                 listUser·p0.999:  17.486 ms/op
                 listUser·p0.9999: 24.515 ms/op
                 listUser·p1.00:   25.100 ms/op

Iteration   3: 4.693 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.747 ms/op
                 listUser·p0.50:   4.530 ms/op
                 listUser·p0.90:   5.251 ms/op
                 listUser·p0.95:   5.595 ms/op
                 listUser·p0.99:   8.192 ms/op
                 listUser·p0.999:  17.400 ms/op
                 listUser·p0.9999: 19.653 ms/op
                 listUser·p1.00:   20.283 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 203755
  mean =      4.708 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12 
    [ 2.500,  5.000) = 171010 
    [ 5.000,  7.500) = 27668 
    [ 7.500, 10.000) = 3936 
    [10.000, 12.500) = 581 
    [12.500, 15.000) = 121 
    [15.000, 17.500) = 177 
    [17.500, 20.000) = 86 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 59 
    [25.000, 27.500) = 86 

  Percentiles, ms/op:
      p(0.0000) =      1.747 ms/op
     p(50.0000) =      4.506 ms/op
     p(90.0000) =      5.243 ms/op
     p(95.0000) =      5.702 ms/op
     p(99.0000) =      8.798 ms/op
     p(99.9000) =     18.325 ms/op
     p(99.9900) =     27.034 ms/op
     p(99.9990) =     28.015 ms/op
     p(99.9999) =     28.017 ms/op
    p(100.0000) =     28.017 ms/op


# Run complete. Total time: 00:13:15

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.979 ± 7.271  ops/ms
ClientPb.existUser                       thrpt       3   8.119 ± 3.831  ops/ms
ClientPb.getUser                         thrpt       3   7.770 ± 5.894  ops/ms
ClientPb.listUser                        thrpt       3   6.972 ± 1.852  ops/ms
ClientPb.createUser                       avgt       3   3.970 ± 1.925   ms/op
ClientPb.existUser                        avgt       3   3.811 ± 0.846   ms/op
ClientPb.getUser                          avgt       3   3.964 ± 2.204   ms/op
ClientPb.listUser                         avgt       3   4.610 ± 0.912   ms/op
ClientPb.createUser                     sample  239059   4.015 ± 0.008   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.423           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.871           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.538           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.210           ms/op
ClientPb.createUser:createUser·p0.99    sample           8.258           ms/op
ClientPb.createUser:createUser·p0.999   sample          23.626           ms/op
ClientPb.createUser:createUser·p0.9999  sample          31.457           ms/op
ClientPb.createUser:createUser·p1.00    sample          33.948           ms/op
ClientPb.existUser                      sample  252781   3.799 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.481           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.715           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.219           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.661           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.832           ms/op
ClientPb.existUser:existUser·p0.999     sample          16.318           ms/op
ClientPb.existUser:existUser·p0.9999    sample          40.763           ms/op
ClientPb.existUser:existUser·p1.00      sample          43.581           ms/op
ClientPb.getUser                        sample  245965   3.901 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.229           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.744           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.309           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.710           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.487           ms/op
ClientPb.getUser:getUser·p0.999         sample          21.135           ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.178           ms/op
ClientPb.getUser:getUser·p1.00          sample          32.342           ms/op
ClientPb.listUser                       sample  203755   4.708 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.747           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.506           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.243           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.702           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.798           ms/op
ClientPb.listUser:listUser·p0.999       sample          18.325           ms/op
ClientPb.listUser:listUser·p0.9999      sample          27.034           ms/op
ClientPb.listUser:listUser·p1.00        sample          28.017           ms/op
