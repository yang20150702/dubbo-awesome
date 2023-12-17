# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.271 ops/ms
# Warmup Iteration   2: 11.959 ops/ms
# Warmup Iteration   3: 12.155 ops/ms
Iteration   1: 12.519 ops/ms
Iteration   2: 12.642 ops/ms
Iteration   3: 12.724 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.628 ±(99.9%) 1.878 ops/ms [Average]
  (min, avg, max) = (12.519, 12.628, 12.724), stdev = 0.103
  CI (99.9%): [10.751, 14.506] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 8.268 ops/ms
# Warmup Iteration   2: 13.061 ops/ms
# Warmup Iteration   3: 13.147 ops/ms
Iteration   1: 13.114 ops/ms
Iteration   2: 13.231 ops/ms
Iteration   3: 13.257 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.201 ±(99.9%) 1.397 ops/ms [Average]
  (min, avg, max) = (13.114, 13.201, 13.257), stdev = 0.077
  CI (99.9%): [11.803, 14.598] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.367 ops/ms
# Warmup Iteration   2: 12.720 ops/ms
# Warmup Iteration   3: 12.921 ops/ms
Iteration   1: 12.891 ops/ms
Iteration   2: 12.970 ops/ms
Iteration   3: 12.817 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.893 ±(99.9%) 1.395 ops/ms [Average]
  (min, avg, max) = (12.817, 12.893, 12.970), stdev = 0.076
  CI (99.9%): [11.498, 14.287] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:45
# Fork: 1 of 1
# Warmup Iteration   1: 6.479 ops/ms
# Warmup Iteration   2: 10.773 ops/ms
# Warmup Iteration   3: 10.746 ops/ms
Iteration   1: 10.725 ops/ms
Iteration   2: 10.835 ops/ms
Iteration   3: 10.694 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.751 ±(99.9%) 1.355 ops/ms [Average]
  (min, avg, max) = (10.694, 10.751, 10.835), stdev = 0.074
  CI (99.9%): [9.397, 12.106] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:39
# Fork: 1 of 1
# Warmup Iteration   1: 4.106 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.616 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.507 ±(99.9%) 0.005 ms/op
Iteration   1: 2.531 ±(99.9%) 0.004 ms/op
Iteration   2: 2.522 ±(99.9%) 0.003 ms/op
Iteration   3: 2.521 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.524 ±(99.9%) 0.099 ms/op [Average]
  (min, avg, max) = (2.521, 2.524, 2.531), stdev = 0.005
  CI (99.9%): [2.425, 2.624] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:34
# Fork: 1 of 1
# Warmup Iteration   1: 3.932 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.455 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.460 ±(99.9%) 0.004 ms/op
Iteration   1: 2.439 ±(99.9%) 0.005 ms/op
Iteration   2: 2.435 ±(99.9%) 0.004 ms/op
Iteration   3: 2.432 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.436 ±(99.9%) 0.057 ms/op [Average]
  (min, avg, max) = (2.432, 2.436, 2.439), stdev = 0.003
  CI (99.9%): [2.379, 2.492] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:29
# Fork: 1 of 1
# Warmup Iteration   1: 3.689 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.498 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.474 ±(99.9%) 0.004 ms/op
Iteration   1: 2.485 ±(99.9%) 0.004 ms/op
Iteration   2: 2.473 ±(99.9%) 0.003 ms/op
Iteration   3: 2.496 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.485 ±(99.9%) 0.211 ms/op [Average]
  (min, avg, max) = (2.473, 2.485, 2.496), stdev = 0.012
  CI (99.9%): [2.273, 2.696] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:24
# Fork: 1 of 1
# Warmup Iteration   1: 4.574 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.007 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.969 ±(99.9%) 0.005 ms/op
Iteration   1: 2.978 ±(99.9%) 0.004 ms/op
Iteration   2: 2.984 ±(99.9%) 0.005 ms/op
Iteration   3: 2.970 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.977 ±(99.9%) 0.131 ms/op [Average]
  (min, avg, max) = (2.970, 2.977, 2.984), stdev = 0.007
  CI (99.9%): [2.846, 3.108] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:19
# Fork: 1 of 1
# Warmup Iteration   1: 4.444 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 2.574 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.530 ±(99.9%) 0.006 ms/op
Iteration   1: 2.520 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.708 ms/op
                 createUser·p0.50:   2.589 ms/op
                 createUser·p0.90:   3.068 ms/op
                 createUser·p0.95:   3.195 ms/op
                 createUser·p0.99:   3.772 ms/op
                 createUser·p0.999:  10.207 ms/op
                 createUser·p0.9999: 13.894 ms/op
                 createUser·p1.00:   14.516 ms/op

Iteration   2: 2.522 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.009 ms/op
                 createUser·p0.50:   2.638 ms/op
                 createUser·p0.90:   3.047 ms/op
                 createUser·p0.95:   3.150 ms/op
                 createUser·p0.99:   3.699 ms/op
                 createUser·p0.999:  8.831 ms/op
                 createUser·p0.9999: 12.936 ms/op
                 createUser·p1.00:   13.156 ms/op

Iteration   3: 2.548 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.740 ms/op
                 createUser·p0.50:   2.617 ms/op
                 createUser·p0.90:   3.092 ms/op
                 createUser·p0.95:   3.215 ms/op
                 createUser·p0.99:   3.940 ms/op
                 createUser·p0.999:  8.941 ms/op
                 createUser·p0.9999: 10.255 ms/op
                 createUser·p1.00:   15.745 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 378960
  mean =      2.530 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 60 
    [ 1.250,  2.500) = 181248 
    [ 2.500,  3.750) = 193581 
    [ 3.750,  5.000) = 3098 
    [ 5.000,  6.250) = 500 
    [ 6.250,  7.500) = 61 
    [ 7.500,  8.750) = 17 
    [ 8.750, 10.000) = 144 
    [10.000, 11.250) = 89 
    [11.250, 12.500) = 70 
    [12.500, 13.750) = 72 
    [13.750, 15.000) = 17 
    [15.000, 16.250) = 3 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.708 ms/op
     p(50.0000) =      2.613 ms/op
     p(90.0000) =      3.072 ms/op
     p(95.0000) =      3.187 ms/op
     p(99.0000) =      3.797 ms/op
     p(99.9000) =      8.880 ms/op
     p(99.9900) =     13.076 ms/op
     p(99.9990) =     14.699 ms/op
     p(99.9999) =     15.745 ms/op
    p(100.0000) =     15.745 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.624 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.446 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.430 ±(99.9%) 0.005 ms/op
Iteration   1: 2.439 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.891 ms/op
                 existUser·p0.50:   2.552 ms/op
                 existUser·p0.90:   2.949 ms/op
                 existUser·p0.95:   3.047 ms/op
                 existUser·p0.99:   3.502 ms/op
                 existUser·p0.999:  5.872 ms/op
                 existUser·p0.9999: 13.795 ms/op
                 existUser·p1.00:   14.549 ms/op

Iteration   2: 2.437 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.937 ms/op
                 existUser·p0.50:   2.515 ms/op
                 existUser·p0.90:   2.957 ms/op
                 existUser·p0.95:   3.068 ms/op
                 existUser·p0.99:   3.621 ms/op
                 existUser·p0.999:  6.728 ms/op
                 existUser·p0.9999: 12.548 ms/op
                 existUser·p1.00:   13.025 ms/op

Iteration   3: 2.427 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.926 ms/op
                 existUser·p0.50:   2.486 ms/op
                 existUser·p0.90:   2.949 ms/op
                 existUser·p0.95:   3.056 ms/op
                 existUser·p0.99:   3.641 ms/op
                 existUser·p0.999:  7.270 ms/op
                 existUser·p0.9999: 13.066 ms/op
                 existUser·p1.00:   13.304 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 393936
  mean =      2.435 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 54 
    [ 1.250,  2.500) = 195587 
    [ 2.500,  3.750) = 195268 
    [ 3.750,  5.000) = 2374 
    [ 5.000,  6.250) = 219 
    [ 6.250,  7.500) = 48 
    [ 7.500,  8.750) = 36 
    [ 8.750, 10.000) = 111 
    [10.000, 11.250) = 44 
    [11.250, 12.500) = 58 
    [12.500, 13.750) = 121 
    [13.750, 15.000) = 16 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.891 ms/op
     p(50.0000) =      2.515 ms/op
     p(90.0000) =      2.953 ms/op
     p(95.0000) =      3.056 ms/op
     p(99.0000) =      3.588 ms/op
     p(99.9000) =      7.014 ms/op
     p(99.9900) =     13.386 ms/op
     p(99.9990) =     14.435 ms/op
     p(99.9999) =     14.549 ms/op
    p(100.0000) =     14.549 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.802 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.549 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.521 ±(99.9%) 0.006 ms/op
Iteration   1: 2.485 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.570 ms/op
                 getUser·p0.50:   2.474 ms/op
                 getUser·p0.90:   3.027 ms/op
                 getUser·p0.95:   3.170 ms/op
                 getUser·p0.99:   3.977 ms/op
                 getUser·p0.999:  10.908 ms/op
                 getUser·p0.9999: 13.470 ms/op
                 getUser·p1.00:   14.221 ms/op

Iteration   2: 2.467 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.879 ms/op
                 getUser·p0.50:   2.507 ms/op
                 getUser·p0.90:   2.998 ms/op
                 getUser·p0.95:   3.109 ms/op
                 getUser·p0.99:   3.699 ms/op
                 getUser·p0.999:  6.400 ms/op
                 getUser·p0.9999: 12.567 ms/op
                 getUser·p1.00:   13.418 ms/op

Iteration   3: 2.481 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.737 ms/op
                 getUser·p0.50:   2.454 ms/op
                 getUser·p0.90:   3.031 ms/op
                 getUser·p0.95:   3.174 ms/op
                 getUser·p0.99:   3.928 ms/op
                 getUser·p0.999:  6.153 ms/op
                 getUser·p0.9999: 10.881 ms/op
                 getUser·p1.00:   11.223 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 387182
  mean =      2.477 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 96 
    [ 1.250,  2.500) = 195892 
    [ 2.500,  3.750) = 186622 
    [ 3.750,  5.000) = 3331 
    [ 5.000,  6.250) = 775 
    [ 6.250,  7.500) = 81 
    [ 7.500,  8.750) = 26 
    [ 8.750, 10.000) = 86 
    [10.000, 11.250) = 109 
    [11.250, 12.500) = 66 
    [12.500, 13.750) = 94 
    [13.750, 15.000) = 4 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.570 ms/op
     p(50.0000) =      2.474 ms/op
     p(90.0000) =      3.019 ms/op
     p(95.0000) =      3.150 ms/op
     p(99.0000) =      3.854 ms/op
     p(99.9000) =      7.427 ms/op
     p(99.9900) =     12.995 ms/op
     p(99.9990) =     13.787 ms/op
     p(99.9999) =     14.221 ms/op
    p(100.0000) =     14.221 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.767 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.037 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.011 ±(99.9%) 0.009 ms/op
Iteration   1: 3.008 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.788 ms/op
                 listUser·p0.50:   2.949 ms/op
                 listUser·p0.90:   3.883 ms/op
                 listUser·p0.95:   4.375 ms/op
                 listUser·p0.99:   5.562 ms/op
                 listUser·p0.999:  9.269 ms/op
                 listUser·p0.9999: 10.600 ms/op
                 listUser·p1.00:   11.436 ms/op

Iteration   2: 2.987 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.892 ms/op
                 listUser·p0.50:   2.929 ms/op
                 listUser·p0.90:   3.883 ms/op
                 listUser·p0.95:   4.358 ms/op
                 listUser·p0.99:   5.579 ms/op
                 listUser·p0.999:  9.040 ms/op
                 listUser·p0.9999: 11.577 ms/op
                 listUser·p1.00:   12.108 ms/op

Iteration   3: 3.002 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.784 ms/op
                 listUser·p0.50:   2.941 ms/op
                 listUser·p0.90:   3.863 ms/op
                 listUser·p0.95:   4.391 ms/op
                 listUser·p0.99:   5.562 ms/op
                 listUser·p0.999:  9.166 ms/op
                 listUser·p0.9999: 11.553 ms/op
                 listUser·p1.00:   12.485 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 319841
  mean =      2.999 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 177 
    [ 1.250,  2.500) = 94485 
    [ 2.500,  3.750) = 186791 
    [ 3.750,  5.000) = 31102 
    [ 5.000,  6.250) = 6033 
    [ 6.250,  7.500) = 599 
    [ 7.500,  8.750) = 261 
    [ 8.750, 10.000) = 206 
    [10.000, 11.250) = 148 
    [11.250, 12.500) = 39 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.784 ms/op
     p(50.0000) =      2.941 ms/op
     p(90.0000) =      3.879 ms/op
     p(95.0000) =      4.375 ms/op
     p(99.0000) =      5.562 ms/op
     p(99.9000) =      9.191 ms/op
     p(99.9900) =     11.436 ms/op
     p(99.9990) =     12.252 ms/op
     p(99.9999) =     12.485 ms/op
    p(100.0000) =     12.485 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.628 ± 1.878  ops/ms
ClientPb.existUser                       thrpt       3  13.201 ± 1.397  ops/ms
ClientPb.getUser                         thrpt       3  12.893 ± 1.395  ops/ms
ClientPb.listUser                        thrpt       3  10.751 ± 1.355  ops/ms
ClientPb.createUser                       avgt       3   2.524 ± 0.099   ms/op
ClientPb.existUser                        avgt       3   2.436 ± 0.057   ms/op
ClientPb.getUser                          avgt       3   2.485 ± 0.211   ms/op
ClientPb.listUser                         avgt       3   2.977 ± 0.131   ms/op
ClientPb.createUser                     sample  378960   2.530 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.708           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.613           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.072           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.187           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.797           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.880           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.076           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.745           ms/op
ClientPb.existUser                      sample  393936   2.435 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.891           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.515           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.953           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.056           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.588           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.014           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.386           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.549           ms/op
ClientPb.getUser                        sample  387182   2.477 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.570           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.474           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.019           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.150           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.854           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.427           ms/op
ClientPb.getUser:getUser·p0.9999        sample          12.995           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.221           ms/op
ClientPb.listUser                       sample  319841   2.999 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.784           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.941           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.879           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.375           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.562           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.191           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.436           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.485           ms/op
